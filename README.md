💾***FF119 Win11 https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/Firefox%20119.rar***

💾***FF109 Win7 https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/Firefox%20109.rar***

▶️***To enable the modified interface, you need the "chrome" folder and the "user.js" file*** (be careful with this file - it makes a "permanent" change to the program settings = to undo the changes, it is not enough to delete it, but you have to manually edit the preferences in "about:config". The way to avoid this manual modification is to backup the file "prefs.js") ***copy into your Firefox profile (about:profiles)***

Firefox installers can be extracted by WinRar/7-Zip and then used without installation. Profiles can be manually created and run via<br/>
***firefox.exe -p<br/>***
or automatically created (if it doesn't already exist) and run via (example)<br/>
***firefox.exe -profile "a:\000"<br/>***

Most of the colors I've changed are pink (FF00A3 and E20074) and orange (FB7914) - they can be easily found/replaced. CSS files can be edited and tested even by your pet = data loaded from it are only temporary in RAM memory and after deleting the files there is no trace of them in the profile or Firefox itself

🚫disabling notifications and downloading updates - create "updates" file in "C:\ProgramData\Mozilla\" (or "C:\ProgramData\MozillaXXX\"). Or deny access (NTFS Permissions Tools). However, these methods may cause a bug in Thunderbird (inability to open settings and browse emails)
<br/>
🚫disabling compatibility check of the profile - delete "compatibility.ini" file and create "compatibility.ini" folder. The profile may or may not be damaged, but its use will no longer be decided by someone else
<br/>
<br/>
<br/>
<img width="720" alt="nahled8" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/bb761add-68aa-40c8-b2af-d341ebe22ed0">
<br/>
<br/>
<br/>
Firefox 119 (2023) - 3-LINE - 1080p ↕️***132px*** - 18,5 + 5 tabs - 150% DPI
![119 - CSS - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/48f40788-2c44-45ad-b7dd-c2d97007de59)

Firefox 119 (2023) - DEFAULT - ↕️***155px*** - 30 tabs - 100% DPI
![119 - default - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/bea14270-7ed3-4800-9679-c001b47e92bf)

Firefox 119 (2023) - DEFAULT - ↕️***231px*** - 15,5 + 5 tabs - 150% DPI
![119 - DEF - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/5b63679b-2546-4c5a-880d-5931260b8a52)

Firefox 119 (2023) - 3-LINE - ↕️***65px*** - 19 + 3 tabs - 150% system DPI - Win11 - "find in page" bar over the address bar. In this case, the entire interface fits into the default "find in page" bar ⬆️😁. Pressing CTRL+F (default hotkey for searching) overlays the address bar, pressing ALT+D (default hotkey for focusing address bar) overlays the find in page bar. The height of the find in page bar should not exceed the height of the bar it overlays, otherwise the page will jump a few pixels when opened. And the overlay only works for the first bar from the bottom - trying to overlay the bar above will just crop the bottom part of the UI and make the page jump again. Example in the image is the only (so far?) possible way to use it seamlessly (overlaying bookmarks or opened tabs doesn't make sense to me = unfortunately does not work in 2-LINE)
<img width="1280" alt="119 - CSS - 150% DPI4" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/7c0cbe8e-4580-491a-aa76-f9f255b9fe08">
```
/* IMPORTANT - find ".findbar-find-previous" (userChrome.css) and change "padding-left" number - example
.findbar-find-previous {padding-left: 213px!important;}
Works in FF 109/119 */
.browserContainer > findbar {-moz-box-ordinal-group: 0!important;order: -1 !important;}
.browserContainer > findbar {max-width: 700px!important;margin-top: -25px!important;} /* if the web content jumps when pressing CTRL+F, the number needs to be adjusted */
.findbar-highlight, .findbar-case-sensitive, .findbar-match-diacritics, .findbar-entire-word {max-width: 10%!important;font-size: 10px !important;margin: 0px!important;margin-top: -2px!important;}
.findbar-find-status {max-width: 2000px!important;}
.findbar-label.findbar-find-status {margin-left: -100px!important;max-width: 20%!important;font-size: 10px !important;}
.findbar-find-status[status="notfound"] {margin-left: 0px!important;font-size: 13px !important;}
.findbar-container {scrollbar-width: none!important;}
.findbar-textbox {position: fixed!important;margin-top: -4px!important;} /* position of the textbox */
```

Firefox 119 (2023) - Pink - opened tabs, orange - bookmarks, without color - history. "width" (userChrome.css *06) and "browser.urlbar.maxRichResults" (about:config or user.js) - 150% DPI
![119 - CSS-address bar - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/27805b1a-0108-4b70-aebb-e88742d2e6bf)
```
/* IMPORTANT - delete "address bar - bookmarks icon position+size / remove url separator" and "address bar - "switch to tab" color" (userChrome.css). Works in FF 109/119 */

/*.urlbarView-row:first-of-type {display: none !important;}*/
.urlbarView-type-icon {display: none !important;}
.urlbarView-action {display: none !important;}
span.urlbarView-title-separator {display: none !important;}
#urlbar .search-panel-one-offs-header-label {display: none !important;}

/* FF119 */
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner > .urlbarView-no-wrap > span.urlbarView-title.urlbarView-overflowable {background-color: #FB7914 !important;color: black !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px !important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner > .urlbarView-no-wrap > span.urlbarView-title.urlbarView-overflowable {background-color: #FF00A3 !important;color: black !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px !important;}

/* FF109 */
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner > .urlbarView-no-wrap > span.urlbarView-title {background-color: #FB7914 !important;color: black !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px !important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner > .urlbarView-no-wrap > span.urlbarView-title {background-color: #FF00A3 !important;color: black !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px !important;}

/* velikost url textu */
.urlbarView-tags, .urlbarView-url, .urlbarView-title:not(:empty) ~ .urlbarView-action {font-size: 1.0em!important;}

/* posunutí url od názvu */
.urlbarView-url {margin-left: 20px !important;}

/* levá mezera pri otevrení adresního rádku */
#urlbar-results {margin-left: 1px!important;}

/* prípadné zvetšení (na výšku) vybraných rádku pomocí myši/klávesnice - zpusobuje neprijemné poskakování textu v prípade nedostatecných mezer mezi rádky */
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner:hover {margin-left: 0px !important;padding-bottom: 0px !important;padding-top: 0px !important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner > .urlbarView-no-wrap:hover {margin-left: 0px !important;padding-bottom: 0px !important;padding-top: 0px !important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner:hover {margin-left: 0px !important;padding-bottom: 0px !important;padding-top: 0px !important;}
.urlbarView-row[type="switchtab"][selected] .urlbarView-row-inner {margin-left: 0px !important;padding-bottom: 0px !important;padding-top: 0px !important;}
.urlbarView-row[type="bookmark"][selected] .urlbarView-row-inner {margin-left: 0px !important;padding-bottom: 0px !important;padding-top: 0px !important;}

/* ikony+text - nevybraný */
.urlbarView-favicon {position: fixed!important;margin-left: 2px !important;}
.urlbarView-title {margin-left: 25px!important;}
/* ikony - vybrané myší */
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner:hover > .urlbarView-no-wrap > .urlbarView-favicon {position: fixed!important;background-color: #FB7914 !important;padding-left: 5px !important;padding-right: 5px !important;margin-left: -3px !important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner:hover > .urlbarView-no-wrap > .urlbarView-favicon {position: fixed!important;background-color: #FF00A3 !important;padding-left: 5px !important;padding-right: 5px !important;margin-left: -3px !important;}
/* text - vybraný myší - FF109 */
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner:hover > .urlbarView-no-wrap > .urlbarView-title {background-color: var(--hover-bg-row) !important;color: var(--hover-text-row) !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px!important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner:hover > .urlbarView-no-wrap > .urlbarView-title {background-color: var(--hover-bg-row) !important;color: var(--hover-text-row) !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px!important;}
/* text - vybraný myší - FF119 */
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner:hover > .urlbarView-no-wrap > span.urlbarView-title.urlbarView-overflowable {background-color: var(--hover-bg-row) !important;color: var(--hover-text-row) !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px!important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner:hover > .urlbarView-no-wrap > span.urlbarView-title.urlbarView-overflowable {background-color: var(--hover-bg-row) !important;color: var(--hover-text-row) !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px!important;}
/* text - vybraný klávesnicí */
.urlbarView-row[type="bookmark"][selected] > .urlbarView-row-inner > .urlbarView-no-wrap > span.urlbarView-title {background-color: var(--hover-bg-row) !important;color: var(--hover-text-row) !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px!important;}
.urlbarView-row[type="switchtab"][selected] > .urlbarView-row-inner > .urlbarView-no-wrap > span.urlbarView-title {background-color: var(--hover-bg-row) !important;color: var(--hover-text-row) !important;padding-left: 2px !important;padding-right: 2px !important;margin-left: 23px!important;}
/* ikony - vybrané klávesnicí */
.urlbarView-row[type="bookmark"][selected] > .urlbarView-row-inner > .urlbarView-no-wrap > .urlbarView-favicon {position: fixed!important;background-color: #FB7914 !important;padding-left: 5px !important;padding-right: 5px !important;margin-left: -3px !important;}
.urlbarView-row[type="switchtab"][selected] > .urlbarView-row-inner > .urlbarView-no-wrap > .urlbarView-favicon {position: fixed!important;background-color: #FF00A3 !important;padding-left: 5px !important;padding-right: 5px !important;margin-left: -3px !important;}
```
Firefox 119 (2023) - Pink - opened tabs, green - bookmarks, without color - history - 150% DPI
![119 - CSS-address bar2 - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/28f85952-7ead-4610-8f9c-ee6117c374fd)
```
/* IMPORTANT - delete "address bar - bookmarks icon position+size / remove url separator" and "address bar - "switch to tab" color" (userChrome.css). Works in FF 109/119 */

/*.urlbarView-row:first-of-type {display: none !important;}*/
.urlbarView-type-icon {display: none !important;}
.urlbarView-action {display: none !important;}
span.urlbarView-title-separator {display: none !important;}
#urlbar .search-panel-one-offs-header-label {display: none !important;}

.urlbarView-row[type="bookmark"] > .urlbarView-row-inner > .urlbarView-no-wrap > .urlbarView-favicon {position: fixed!important;background-color: #40E0D0 !important;padding-left: 5px !important;padding-right: 5px !important;margin-left: -2px !important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner > .urlbarView-no-wrap > .urlbarView-favicon {position: fixed!important;background-color: #FF00A3 !important;padding-left: 5px !important;padding-right: 5px !important;margin-left: -2px !important;}
.urlbarView-row[type="bookmark"] > .urlbarView-row-inner > .urlbarView-no-wrap > .urlbarView-title {margin-left: 27px!important;}
.urlbarView-row[type="switchtab"] > .urlbarView-row-inner > .urlbarView-no-wrap > .urlbarView-title {margin-left: 27px!important;}

/* velikost url textu */
.urlbarView-tags, .urlbarView-url, .urlbarView-title:not(:empty) ~ .urlbarView-action {font-size: 1.0em!important;}
/* posunutí url od názvu */
.urlbarView-url {margin-left: 30px !important;}
/* levá mezera pri otevrení adresního rádku */
#urlbar-results {margin-left: 1px!important;}
/* ikony+text - nevybraný */
.urlbarView-favicon {position: fixed!important;margin-left: 3px !important;}
.urlbarView-title {margin-left: 27px!important;}
```

Firefox 119 (2023) - DEFAULT - opened tabs+bookmarks+history - 150% DPI
![119 - CSS-address bar3 - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/15ea7ef9-0cce-44d2-89aa-0a5072ea7e67)

Firefox 119 (2023) - DEFAULT - ↕️***478px*** - 150% system DPI. 44% of the screen is occupied by UI? It's probably time to buy a bigger monitor...
<img width="1280" alt="119 - CSS - 150% DPI5" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/82132e52-0e06-477e-ab09-aa5ce9787d9d">

Firefox 109 (2023) - 1-LINE - ↕️***34px*** 150% DPI
<img width="1280" alt="Firefox (150% DPI) - oneline" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/ee58cc66-191e-4e1b-9ed3-c10ea5459723">

Firefox 109 (2023) - 3-LINE - 150% system DPI
![Firefox (150% DPI) - compact default](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/487f32f5-49f4-4df1-ba1a-04ffe14d3f23)

Firefox 109 (2023) - 2-LINE - folder+context menu - 150% DPI
![Firefox (150% DPI) - folder+context menu](https://user-images.githubusercontent.com/127822397/232291657-785f1fa4-68d8-4d4f-b0e1-8acc19624c7a.png)

Firefox 109 (2023) - 2-LINE - places.xhtml. Dark space - The best dynamic theme - 150% DPI
![Firefox (150% DPI) - places xhtml](https://user-images.githubusercontent.com/127822397/232334393-15d759a9-e31b-4a30-8d59-f74ec96b0427.png)

Firefox 119 (2023) - 2-LINE - ↕️***64px*** 150% DPI
![119 - CSS-2-LINE - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/5a963df3-8c71-4c8a-97f1-ac99f74e270d)

Firefox 119 (2023) - DEFAULT - ↕️***85px*** 100% DPI
![119 - DEF-2-LINE - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/288daae3-ed5c-4165-9dc5-2ce9849f3723)

Firefox 109 (2023) - 2-LINE - ↕️***67px*** 150% DPI
![109 - CSS - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/151487eb-1c16-48c6-bd1d-ef37ec4f42d8)

Firefox 109 (2023) - DEFAULT - ↕️***85px*** 100% DPI
![109 - DEF - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/56afb603-3962-4152-9518-7a9ac65129d7)

Firefox 99 (2022) - 2-LINE ↕️***64px*** - 33,5 opened tabs - smallest tab width (about:config "browser.tabs.tabMinWidth") - 150% DPI
<img width="1280" alt="Firefox (150% DPI) - compact" src="https://user-images.githubusercontent.com/127822397/234294708-65de1f44-8723-42ad-8c16-1d44ac7aefa8.png">

Firefox 99 (2022) - DEFAULT ↕️***85px*** 30 opened tabs - 100% DPI
<img width="1280" alt="099 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/564f68bc-3263-41be-8790-6a68b1f2398b">

Firefox 89 (2021) - 2-LINE ↕️***61px*** 150% DPI
<img width="1280" alt="089 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/0e33a1bb-14d9-4d55-aba4-83536c444eca">

Firefox 89 (2021) - DEFAULT ↕️***85px*** 100% DPI
<img width="1280" alt="089 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/a55bcd9d-6a3f-4940-bd3d-381f5e7c0d27">

Firefox 79 (2020) - 2-LINE ↕️***61px*** 150% DPI
<img width="1280" alt="079 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/18e53d69-2ec5-43f1-9ec3-650ee8d0b01c">

Firefox 79 (2020) - DEFAULT ↕️***74px*** 100% DPI
<img width="1280" alt="079 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/edab11b7-0771-49cf-92db-eecc0369c01a">

Firefox 69 (2019) - 2-LINE ↕️***64px*** 150% DPI
<img width="1280" alt="069 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/8ba89a97-ad17-43c7-9fc6-b8772cb6e2c0">

Firefox 69 (2019) - DEFAULT ↕️***74px*** 100% DPI
<img width="1280" alt="069 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/b1ef0974-47aa-4883-88c5-18b98854cd2b">

Firefox 59 (2018) - 2-LINE ↕️***65px - opening menu bar in FF59- through ALT+arrows*** - 150% DPI
<img width="1280" alt="059 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/f691cfca-ae43-434e-ba8e-dbeea2447117">

Firefox 59 (2018) - DEFAULT ↕️***73px*** 100% DPI
<img width="1280" alt="059 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/00bbb9f8-9533-406f-986e-ed7e6da151c8">

Firefox 49 (2016) - 2-LINE ↕️***68px*** 150% DPI
<img width="1280" alt="049 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/3c58188f-8e72-4d69-b3f9-1f24a858410f">

Firefox 49 (2016) - DEFAULT ↕️***71px*** 100% DPI
<img width="1280" alt="Firefox 49 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/ce717463-65f1-47c3-9206-4a3b3ffa74ab">

Firefox 39 (2015) - 2-LINE ↕️***65px*** 150% DPI
<img width="1280" alt="039 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/4bc30f4b-7d86-43eb-9665-ddfa4c49661c">

Firefox 39 (2015) - DEFAULT ↕️***71px*** 100% DPI
<img width="1280" alt="039 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/f3ebdc14-293b-4ed0-a8a9-1b0889a1e23c">

Firefox 29 (2014) - 2-LINE ↕️***64px*** 150% DPI
<img width="1280" alt="029 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/b6a20a17-2c82-46d6-8737-49300428d959">

Firefox 29 (2014) - DEFAULT ↕️***71px*** 100% DPI
![029 (100% DPI)-DEFAULT](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/21d733dd-1928-4092-8792-2681db9466b0)

Firefox 19 (2013) - 2-LINE ↕️***66px*** 150% DPI
<img width="1280" alt="019 - CSS3 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/d83e706a-a183-4f1f-8317-a978143ef671">

Firefox 19 (2013) - DEFAULT ↕️***63px*** 100% DPI
<img width="1280" alt="019 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/05739ab3-8fc7-4d90-a50d-e3c37c3e9434">

Firefox 9 (2011) - 2-LINE ↕️***64px*** 150% DPI
<img width="1280" alt="009 - CSS3 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/829675ee-b28d-412c-92d2-44be9ee7fb53">

Firefox 9 (2011) - DEFAULT ↕️***64px*** 100% DPI
<img width="1280" alt="009 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/a3751eef-a46a-4119-9277-a80e9fb056dc">

Firefox 3.5 (2009-2011) - 2-LINE ↕️***67px*** - "find in page" bar over the address bar - 150% DPI
<img width="1280" alt="003 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/4ac78e83-496f-4199-a94d-00775d24ac9e">

Firefox 3.5 (2009-2011) - DEFAULT ↕️***169px*** 150% DPI
<img width="1280" alt="003-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/d5262193-2ab2-432b-b1e8-13da2ffe1fa9">

Firefox 2 (2006-2008) - 2-LINE ↕️***65px*** 150% DPI
<img width="1280" alt="002 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/6e1afe69-67f8-49e6-8c9a-d6f733395606">

Firefox 2 (2006-2008) - DEFAULT ↕️***103px*** 100% DPI
<img width="1280" alt="Firefox 002-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/0e703934-25f9-4689-8d99-a59bffefc6de">

Customization (userChrome.css)
<img width="1280" alt="Customization" src="https://user-images.githubusercontent.com/127822397/235342097-4f9103a9-7211-4d33-b17b-600c438eee2f.png">

***custom keyboard shortcuts.ahk (Autohotkey v1.1)***
<br/>
F1 - Library window (History) CTRL+SHIFT+H
<br/>
F2 - Find Previous (searchbar)
<br/>
F3 - Find Next (searchbar) - works without script
<br/>
Home - New Tab
<br/>
END - Close Tab
<br/>
PgUp - Go one Tab to the Right
<br/>
PgDn - Go one Tab to the Left
<br/>
INS - Focus Address bar
<br/>
Del (hold 0.5 second) - Copy URL (Activate Bottom "Notepad++", KeyWait CTRL+V and Activate Bottom "Firefox" is disabled)

***suggestions for improvements***
<br/>
-remove the titles/checkboxes in the "find in page" bar and replace them with buttons/icons
<br/>
-show all downloads in the pop-up window (with scrollbar) and get rid of the "show all downloads" window
<br/>
-renaming bookmarks directly (long/short right mouse click)
<br/>
-tabs with play/pause button and hotkey (remove useless volume button)
<br/>
-combine "Edit Folder/Bookmark" in the context menu into a single entry at one specific position (properties in FF79-)
<br/>
-popup status bar around mouse cursor
<br/>
-remove 3 dots in bookmarks names (if are too long)
<br/>
-add-ons in the "Customize Toolbar" menu
<br/>
-decrease mouse vert sensitivity when the cursor approaches the left/right sides of bookmarks (folders)
<br/>
-separate audio/video cache from normal cache. What's the point of the current setup where important cache data is overwritten by useless video that also reduces SSD lifetime? Constantly modifying NTFS permissions for cache folder is not very comfortable...

***Useful addons***
<br/>
***Avast Online Security*** https://addons.mozilla.org/en-US/firefox/addon/avast-online-security/
<br/>
***Enhancer for YouTube*** https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube/
<br/>
***YouTube Ad Auto-skipper*** https://addons.mozilla.org/en-US/firefox/addon/youtube-ad-auto-skipper/
<br/>
***Hide YouTube Fullscreen Controls*** https://addons.mozilla.org/en-US/firefox/addon/hide-youtube-controls/
<br/>
***SaveFrom.net helper*** https://addons.mozilla.org/en-US/firefox/addon/savefromnet-helper/
<br/>
***I don't care about cookies*** https://addons.mozilla.org/en-US/firefox/addon/i-dont-care-about-cookies/
<br/>
***Disable HTML5 Autoplay*** https://addons.mozilla.org/en-US/firefox/addon/disable-autoplay/
<br/>
***Image Video Block*** https://addons.mozilla.org/en-US/firefox/addon/image-video-block/
<br/>
***Large Image Blocker*** https://addons.mozilla.org/en-US/firefox/addon/large-image-blocker/
<br/>
***Gif Blocker*** https://addons.mozilla.org/en-US/firefox/addon/gif-blocker/
<br/>
***Load Background Tabs Lazily*** https://addons.mozilla.org/en-US/firefox/addon/load-background-tabs-lazily/
<br/>
***Print Edit WE + Save Page WE*** https://addons.mozilla.org/en-US/firefox/addon/print-edit-we/ https://addons.mozilla.org/en-US/firefox/addon/save-page-we/
<br/>
***Firefox Color*** https://addons.mozilla.org/en-US/firefox/addon/firefox-color/

***https://www.reddit.com/r/FirefoxCSS/***
<br/>
***https://firefoxcss-store.github.io/***
<br/>
***https://www.userchrome.org/***
<br/>

***about:about***
<br/>
***about:downloads***
<br/>
***chrome://browser/content/places/places.xhtml***
<br/>
***https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html***
<br/>
***https://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly***
<br/>
***https://www.mozilla.org/en-US/firefox/releases/***
<br/>
***https://whattrainisitnow.com/calendar/***
<br/>
***https://ftp.mozilla.org/pub/firefox/releases/***
<br/>
***https://ftp.mozilla.org/pub/devedition/releases/***

about:config

***dpi***
<br/>
layout.css.devPixelsPerPx

***turning off the full screen warning***
<br/>
full-screen-api.warning.timeout;0

***default zooming of PDF files***
<br/>
pdfjs.defaultZoomValue;page-width

***find in page - colors***
<br/>
ui.textSelectBackgroundAttention
<br/>
ui.textHighlightBackground
<br/>
ui.textHighlightForeground

***new tab - color***
<br/>
browser.display.background_color;#eeeeee

***scrollbars***
<br/>
widget.non-native-theme.scrollbar.size
<br/>
widget.non-native-theme.win.scrollbar.use-system-size
<br/>
widget.non-native-theme.scrollbar.size.override
<br/>
widget.disable-dark-scrollbar
<br/>
widget.non-native-theme.win11.scrollbar.force-overlay-style
<br/>
widget.windows.overlay-scrollbars.enabled

***disabling tooltips when hovering over bookmarks***
<br/>
browser.chrome.toolbar_tips

***disable animations (interface of the program and the website itself) - probably no need to be afraid of blindly toggling the "animat" and "transition" preferences***
<br/>
browser.fullscreen.animate;false
<br/>
browser.tabs.animate;false
<br/>
image.animation_mode;none
<br/>
ui.prefersReducedMotion;1
<br/>
svg.disabled;true
<br/>
full-screen-api.transition-duration.leave
<br/>
full-screen-api.transition-duration.enter

***a compact density option will be added to the "customize toolbar" menu***
<br/>
browser.compactmode.show

***set compact density immediately by number 1***
<br/>
browser.uidensity

***disable the graphical user interface "Proton"***
<br/>
browser.proton.enabled

***address bar - number of items***
<br/>
browser.urlbar.maxRichResults

***address bar - disable autoFill***
<br/>
browser.urlbar.autoFill;false

***address bar - disable search engine***
<br/>
keyword.enabled;false

***address bar - disable "Firefox suggest"***
<br/>
browser.urlbar.groupLabels.enabled;false

***address bar - disable faded font***
<br/>
browser.urlbar.formatting.enabled;false

***address bar - hide reader icon***
<br/>
reader.parse-on-load.enabled;false

***tabs - disable previews when dragging***
<br/>
nglayout.enable_drag_images;false

***tabs - minimum width***
<br/>
browser.tabs.tabMinWidth

***tabs pinned - disable autoreload***
<br/>
browser.sessionstore.restore_pinned_tabs_on_demand

***disable the request to delete settings when the browser is not started for a long time***
<br/>
browser.disableResetPrompt;true

***disable query to enable DRM***
<br/>
browser.eme.ui.enabled;false

***slow Firefox startup - turn off notifications***
<br/>
browser.slowStartup.notificationDisabled

***do not turn off firefox when closing the last tab***
<br/>
browser.tabs.closeWindowWithLastTab;false

***open in tabs only***
<br/>
browser.link.open_newwindow.restriction;0

***location query***
<br/>
geo.enabled

***disable "insecure login" warning***
<br/>
security.insecure_field_warning.contextual.enabled;false

***ctrl+shift+j***
<br/>
devtools.chrome.enabled;true

***disable autoplay***
<br/>
media.autoplay.enabled;false
<br/>
media.autoplay.allow-muted;false

***enable support for WEBM playback***
<br/>
media.mediasource.webm.enabled

***disable enforcement of signing add-ons***
<br/>
xpinstall.signatures.required;false

***disable blacklisting of add-ons***
<br/>
extensions.blocklist.enabled;false

***not to allow arbitrary banning of add-ons***
<br/>
extensions.legacy.enabled;true

***do not save the list of currently opened tabs to disk = reduce writing to SSD***
<br/>
browser.sessionstore.resume_from_crash;false

***do not create bookmarks backups***
<br/>
browser.bookmarks.max_backups;0

***disabling automatic page refresh***
<br/>
accessibility.blockautorefresh;true

***maximum cache size on SSD***
<br/>
browser.cache.disk.capacity

***maximum size of the cached file on the SSD***
<br/>
browser.cache.disk.max_entry_size

***cache isolation***
<br/>
browser.cache.cache_isolation;true

***connection timeout***
<br/>
network.http.connection-timeout

***firefox.exe - priority "normal"***
<br/>
dom.ipc.processPriorityManager.enabled;false

***limiting the number of firefox.exe processes (the advantage is less CPU+RAM requirements and the disadvantage is worse security)***
<br/>
fission.autostart;false
