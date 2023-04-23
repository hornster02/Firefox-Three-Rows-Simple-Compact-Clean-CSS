To enable the modified interface, you need the "chrome" folder and the "user.js" file (be careful with this file - it makes a "permanent" change to the program settings = to undo the changes, it is not enough to delete it, but you have to manually edit the preferences in "about:config". The way to avoid this manual modification is to backup the file "prefs.js") copy into your Firefox profile

-Firefox installers can be extracted by WinRar and then used without installation. Profiles can be created and run via firefox.exe -p

-download FF109
https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/blob/main/Firefox%20109.rar?raw=true

Firefox CSS - same vertical size of UI (230% DPI + 14 tabs). "layout.css.devPixelsPerPx" (about:config or "user.js")
![_firefox (230% DPI +14 tabs) - tweak](https://user-images.githubusercontent.com/127822397/224916988-b476808b-f8d1-4407-85f8-04ef3d84cb32.jpg)
Firefox default - same vertical size of UI (141% DPI + 14 tabs)
![_firefox (141% DPI +14 tabs) - default](https://user-images.githubusercontent.com/127822397/224916984-2d8509f7-f7d5-4ac2-bd50-707ecce482c0.jpg)
Chrome default - same vertical size of UI (150% DPI + 14 tabs)
![_chrome (150% DPI +14 tabs) - default](https://user-images.githubusercontent.com/127822397/224916993-bced2d87-2cf3-48bf-bb2b-0f60183faeb8.jpg)
Firefox Compact (set via the customize toolbar). 150% DPI + 33,5 tabs - smallest tab width (about:config "browser.tabs.tabMinWidth") = 100% more tabs than Chrome
<img width="1280" alt="Firefox (150% DPI) - compact" src="https://user-images.githubusercontent.com/127822397/227723363-ead772f4-1546-4303-8fa0-574c953a0fd6.png">
Firefox (150% DPI) - folder+context menu
![Firefox (150% DPI) - folder+context menu](https://user-images.githubusercontent.com/127822397/232291657-785f1fa4-68d8-4d4f-b0e1-8acc19624c7a.png)
Firefox (150% DPI) - urlbar. Line "address bar - width when opened" (userChrome.css). And "browser.urlbar.maxRichResults" (about:config or "user.js"). Dark space - The best dynamic theme
<img width="1280" alt="Firefox (150% DPI) - urlbar" src="https://user-images.githubusercontent.com/127822397/233781701-4a952f36-77dc-41ab-ac8c-2826b8482c6d.png">
Firefox (150% DPI) - places.xhtml. Dark space - The best dynamic theme
![Firefox (150% DPI) - places xhtml](https://user-images.githubusercontent.com/127822397/232334393-15d759a9-e31b-4a30-8d59-f74ec96b0427.png)

Firefox (150% DPI) - find on page
<img width="1280" alt="Firefox (150% DPI) - find on page" src="https://user-images.githubusercontent.com/127822397/232224698-6a0ef5d3-650e-485f-9dc2-908f300657db.png">

Firefox Simple (150% DPI). Line "remove all remaining icons" (userChrome.css)
<img width="1280" alt="Firefox (150% DPI)" src="https://user-images.githubusercontent.com/127822397/232224216-c089e8fb-52b0-4ebe-9ba6-12419f03fa2f.png">

Firefox 59 (150% DPI)
<img width="1280" alt="Firefox 59 (150% DPI)" src="https://user-images.githubusercontent.com/127822397/233847178-04672570-3aa9-458e-846f-2199f0fcdcfe.png">

-custom keyboard shortcuts.ahk (Autohotkey)

F1 - Library window (History) CTRL+SHIFT+H

F2 - Find Previous (searchbar)

F3 - Find Next (searchbar) - works without script

Home - New Tab

END - Close Tab

PgUp - Go one Tab to the Right

PgDn - Go one Tab to the Left

INS - Focus Address bar

Del - Copy URL (Activate Bottom "Notepad++", KeyWait CTRL+V and Activate Bottom "Firefox" is disabled)
