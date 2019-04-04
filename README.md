# dictation-bug

- Set focus to UITextView
- Tap Bold button (calls UITextView.toggleBoldface)
=> UITextView.typingAttributes now has bold font
- turn on Dictation
- speak
=> observe that bold text is inserted as you speak
- tap to dismiss keyboard
=> observe that final inserted text is not bold
Bug: font set in typingAttributes is lost and font from surrounding text is used

