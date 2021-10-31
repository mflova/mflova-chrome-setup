# mflova-chrome.steup
To use it, install google chrome and its extension called "Vimium"

### Main chrome use
|Command/shortcut| Description|
|----------------|------------|
|ctrl+t|New tab|
|ctrl+w|Close tab|
|ctrl+avpag/repag|Next or previous tab|
|ctrl+number|Chose a tab|
|ctrl+l|Select the URL bar|
|ctrl+a|Select all|
|alt+left/right arrows|Go back/forward in history|

### Main Vimium use
|Command/shortcut| Description|
|----------------|------------|
|f|Select keywords from the website. If shift is pressed when finished, it will be opened in a new tab|
|o| Fuzzy find history AND bookmarks. Shift to open in new tab|
|b| Fuzzy find bookmarks. Shift to open in new tab|
|T| Fuzzy find among opened tabs|
|/| Search for a word. You can use n or N to go back and forward in occurences|

If I wanted to copy a line from the website:
- Search the first chars with / to situate the cursor on the expression
- Enter
- v to enter visual mode
- Use keys such as w(next word) or $(end of the line) to highlight what you want
- y(yank) or ctrl+c to copy. Both are the same
