***download FF119 Win11 https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/Firefox%20119.rar***

***download FF109 Win7 https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/Firefox%20109.rar***

***To enable the modified interface, you need the "chrome" folder and the "user.js" file*** (be careful with this file - it makes a "permanent" change to the program settings = to undo the changes, it is not enough to delete it, but you have to manually edit the preferences in "about:config". The way to avoid this manual modification is to backup the file "prefs.js") ***copy into your Firefox profile (about:profiles)***

-Firefox installers can be extracted by WinRar/7-Zip and then used without installation. Profiles can be manually created and run via<br/>
***firefox.exe -p<br/>***
or automatically created (if it doesn't already exist) and run via (example)<br/>
***firefox.exe -profile "a:\000"<br/>***
-disabling notifications and downloading updates - create "updates" file in "C:\ProgramData\Mozilla\" (or "C:\ProgramData\MozillaXXX\"). Or deny access (NTFS Permissions Tools)
<br/>
-disabling compatibility check of the profile - delete "compatibility.ini" file and create "compatibility.ini" folder. The profile may or may not be damaged, but its use will no longer be decided by someone else

Firefox 119 (2023) - 3-LINE - 1080p ↕️***132px*** - 18,5 + 5 tabs - 150% DPI
![119 - CSS - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/48f40788-2c44-45ad-b7dd-c2d97007de59)

Firefox 119 (2023) - DEFAULT - 1080p ***155px*** 100% DPI
![119 - default - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/bea14270-7ed3-4800-9679-c001b47e92bf)

Firefox 119 (2023) - DEFAULT - 1080p ***231px*** - 15,5 + 5 tabs - 150% DPI
![119 - DEF - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/5b63679b-2546-4c5a-880d-5931260b8a52)

Firefox 119 (2023) - 3-LINE - 1080p ***65px*** - 19 + 3 tabs - 150% DPI - "find in page" bar over the address bar. In this case, the entire interface fits into the default "find in page" bar ⬆️ 😁
![119 - CSS - 150% DPI4](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/9162ea07-69ee-484a-83b9-e78ff06011dd)
```
/* IMPORTANT - find ".findbar-find-previous" (userChrome.css) and change "padding-left" number - example
.findbar-find-previous {padding-left: 213px!important;}
Works in FF 109/119
*/
.browserContainer > findbar {-moz-box-ordinal-group: 0!important;order: -1 !important;}
.browserContainer > findbar {max-width: 700px!important;margin-top: -25px!important;} /* if the web content jumps when pressing CTRL+F, the number needs to be adjusted */
.findbar-highlight, .findbar-case-sensitive, .findbar-match-diacritics, .findbar-entire-word {max-width: 10%!important;font-size: 10px !important;margin: 0px!important;margin-top: -2px!important;}
.findbar-find-status {max-width: 2000px!important;}
.findbar-label.findbar-find-status {margin-left: -100px!important;max-width: 20%!important;font-size: 10px !important;}
.findbar-find-status[status="notfound"] {margin-left: 0px!important;font-size: 13px !important;}
.findbar-container {scrollbar-width: none!important;}
.findbar-textbox {position: fixed!important;margin-top: -4px!important;} /* position of the textbox */
```

Firefox 119 (2023) - 2-LINE - ***64px*** 150% DPI
![119 - CSS-2-LINE - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/5a963df3-8c71-4c8a-97f1-ac99f74e270d)

Firefox 109 (2023) - 1-LINE - ***34px*** 150% DPI
<img width="1280" alt="Firefox (150% DPI) - oneline" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/ee58cc66-191e-4e1b-9ed3-c10ea5459723">

Firefox 109 (2023) - 2-LINE - ***67px*** 150% DPI
![109 - CSS - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/151487eb-1c16-48c6-bd1d-ef37ec4f42d8)

Firefox 109 (2023) - 3-LINE - 150% DPI
<img width="1280" alt="Firefox (150% DPI) - compact default" src="https://user-images.githubusercontent.com/127822397/235430973-1cddca02-26a9-4435-b1e4-16972b82a6e7.png">

Firefox 109 (2023) - folder+context menu - 150% DPI
![Firefox (150% DPI) - folder+context menu](https://user-images.githubusercontent.com/127822397/232291657-785f1fa4-68d8-4d4f-b0e1-8acc19624c7a.png)

Firefox 109 (2023) - urlbar. "width" (userChrome.css *06) and "browser.urlbar.maxRichResults" (about:config or user.js). Dark space - The best dynamic theme - 150% DPI
<img width="1280" alt="Firefox (150% DPI) - urlbar" src="https://user-images.githubusercontent.com/127822397/233781701-4a952f36-77dc-41ab-ac8c-2826b8482c6d.png">

Firefox 109 (2023) - places.xhtml. Dark space - The best dynamic theme - 150% DPI
![Firefox (150% DPI) - places xhtml](https://user-images.githubusercontent.com/127822397/232334393-15d759a9-e31b-4a30-8d59-f74ec96b0427.png)

Firefox 99 (2022) - 2-LINE ***64px*** - 33,5 opened tabs - smallest tab width (about:config "browser.tabs.tabMinWidth") - 150% DPI
<img width="1280" alt="Firefox (150% DPI) - compact" src="https://user-images.githubusercontent.com/127822397/234294708-65de1f44-8723-42ad-8c16-1d44ac7aefa8.png">

Firefox 99 (2022) - DEFAULT ***85px*** 30 opened tabs - 100% DPI
<img width="1280" alt="099 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/564f68bc-3263-41be-8790-6a68b1f2398b">

Firefox 89 (2021) - 2-LINE ***61px*** 150% DPI
<img width="1280" alt="089 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/0e33a1bb-14d9-4d55-aba4-83536c444eca">

Firefox 89 (2021) - DEFAULT ***85px*** 100% DPI
<img width="1280" alt="089 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/a55bcd9d-6a3f-4940-bd3d-381f5e7c0d27">

Firefox 79 (2020) - 2-LINE ***61px*** 150% DPI
<img width="1280" alt="079 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/18e53d69-2ec5-43f1-9ec3-650ee8d0b01c">

Firefox 79 (2020) - DEFAULT ***74px*** 100% DPI
<img width="1280" alt="079 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/edab11b7-0771-49cf-92db-eecc0369c01a">

Firefox 69 (2019) - 2-LINE ***64px*** 150% DPI
<img width="1280" alt="069 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/8ba89a97-ad17-43c7-9fc6-b8772cb6e2c0">

Firefox 69 (2019) - DEFAULT ***74px*** 100% DPI
<img width="1280" alt="069 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/b1ef0974-47aa-4883-88c5-18b98854cd2b">

Firefox 59 (2018) - 2-LINE ***65px - opening menu bar in FF59- through ALT+arrows*** - 150% DPI
<img width="1280" alt="059 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/f691cfca-ae43-434e-ba8e-dbeea2447117">

Firefox 59 (2018) - DEFAULT ***73px*** 100% DPI
<img width="1280" alt="059 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/00bbb9f8-9533-406f-986e-ed7e6da151c8">

Firefox 49 (2016) - 2-LINE ***68px*** 150% DPI
<img width="1280" alt="049 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/3c58188f-8e72-4d69-b3f9-1f24a858410f">

Firefox 49 (2016) - DEFAULT ***71px*** 100% DPI
<img width="1280" alt="Firefox 49 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/ce717463-65f1-47c3-9206-4a3b3ffa74ab">

Firefox 39 (2015) - 2-LINE ***65px*** 150% DPI
<img width="1280" alt="039 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/4bc30f4b-7d86-43eb-9665-ddfa4c49661c">

Firefox 39 (2015) - DEFAULT ***71px*** 100% DPI
<img width="1280" alt="039 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/f3ebdc14-293b-4ed0-a8a9-1b0889a1e23c">

Firefox 29 (2014) - 2-LINE ***64px*** 150% DPI
<img width="1280" alt="029 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/b6a20a17-2c82-46d6-8737-49300428d959">

Firefox 29 (2014) - DEFAULT ***71px*** 100% DPI
![029 (100% DPI)-DEFAULT](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/21d733dd-1928-4092-8792-2681db9466b0)

Firefox 19 (2013) - 2-LINE ***66px*** 150% DPI
<img width="1280" alt="019 - CSS3 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/d83e706a-a183-4f1f-8317-a978143ef671">

Firefox 19 (2013) - DEFAULT ***63px*** 100% DPI
<img width="1280" alt="019 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/05739ab3-8fc7-4d90-a50d-e3c37c3e9434">

Firefox 9 (2011) - 2-LINE ***64px*** 150% DPI
<img width="1280" alt="009 - CSS3 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/829675ee-b28d-412c-92d2-44be9ee7fb53">

Firefox 9 (2011) - DEFAULT ***64px*** 100% DPI
<img width="1280" alt="009 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/a3751eef-a46a-4119-9277-a80e9fb056dc">

Firefox 3.5 (2009-2011) - 2-LINE ***67px*** - "find in page" bar over the address bar - 150% DPI
<img width="1280" alt="003 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/4ac78e83-496f-4199-a94d-00775d24ac9e">

Firefox 3.5 (2009-2011) - DEFAULT ***169px*** 150% DPI
<img width="1280" alt="003-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/d5262193-2ab2-432b-b1e8-13da2ffe1fa9">

Firefox 2 (2006-2008) - 2-LINE ***65px*** 150% DPI
<img width="1280" alt="002 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/6e1afe69-67f8-49e6-8c9a-d6f733395606">

Firefox 2 (2006-2008) - DEFAULT ***103px*** 100% DPI
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
<br/>
***https://github.com/hornster02/Autohotkey_AHK_H2***

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
