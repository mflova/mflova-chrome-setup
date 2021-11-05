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


### CVIM - Chromium-vim
How to modify main options:
In order to edit the options, go to background_scripts/options.js and modify the required options. Then go to the root of chromium-vim and run:
 - npm install
 - make
 - Go to chrome > options > more tools > extensions > load unpacked > folder to cvim
This has to be done every time this script is changed. 

Since this plugin based on Vimium does not work in google chrome new tabs, it is recommmended to install "New tab redirect" plugin and set a page like "blank.org".

If the configuration is not loaded properly try one of these:
- Ensure that the path in background_scripts/options.js configpath: is set up correctly
- Execute :source <path_to_cvimrc>

General note: All the shortcuts that have an equivalent capital letter will perform the action in a new tab.
|Command/shortcut| Description|
|----------------|------------|
| Tab/Shift+Tab | Move between the options in the menu|
| h/H | Fuzzy finder history |
| b/B | Fuzzy finder bookmarks |
|f/F|Select keywords from the website|
|p/P| Print the clipboard in the URL bar|
|wj/WJ|Opens Jira |
|wg/WG|Opens Gmail|
|wd/WD|Opens Google drive|
|wc/WC|Opens Google calendar|
|wh/WH|Opens Holaspirit|
|wo/WO|Opens Odoo|
