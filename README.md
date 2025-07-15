⬇️ [Historical comparison](#historical-comparison) / [Useful addons + about:config](#useful-addons-about-config) / [Other](#other) ⬇️

Mar 14, 2023 - Jun 15, 2025

Firefox 117+ is working again in Win7 ***[kernel1](https://github.com/YuZhouRen86/VxKex-NEXT) [2](https://github.com/i486/VxKex) [3](https://github.com/vxiiduu/VxKex) or [FF](https://github.com/e3kskoy7wqk/Firefox-for-windows-7)***
<br/>
-without ```user_pref("media.rdd-wav.enabled", false);``` (prefs.js) FF140 may not run in Win7

CSS Calendar - ***FF - next ESR release + 1 month*** (2026), ***TB - skip 1 ESR release + 1 month*** (2027)

***android - [📥 desktop mode as default + fullscreen](https://github.com/hornster02/hornster02/raw/main/android.rar)***
<br/>

***Firefox CSS - [📥 140](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/140-esr(9-140+)_gen2.rar)⠀[📥 themes (light)](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/theme.rar)⠀[📥 Autohotkey v1.1 ⬇️](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/script.rar)***

```
ESC (hold) - Page with/out style switch (buggy - it needs to be rewritten)
Tab (hold) - switching between last 2 tabs
F2 - Find Previous (searchbar)
F3 - Find Next (searchbar) - works without script
INS - Focus Address bar (press) / Address bar history (hold)
Del (hold) - copy URL. Activate bottom Notepad++, keywait CTRL+V and activate bottom Firefox is disabled
Home - New Tab (press) / Address bar bookmarks (hold)
END - Close Tab
PgUp - Go one Tab to Right (press) / Address bar tabs (hold)
PgDn - Go one Tab to Left
F1 - Bookmarks (press) / History (hold) / Downloaded (double) [places.xhtml, focus on search, open in tab 1 =
address bar+download button+side bar alternative] + Enter for opening in new tab (press/hold), CZ/EN FF
```

***Thunderbird CSS - [📥 140](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/140-esr-thunderbird.rar)⠀[📥 115](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/115-esr-thunderbird.rar)⠀[📥 theme](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/theme-thunderbird.rar)⠀[📥 Autohotkey v1.1 ⬇️](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/script-thunderbird.rar)***

```
F2 - Find Previous (searchbar, press) + Rename (hold)
F3 - Find Next (searchbar) - works without script
INS - Focus search bar (press) / Focus filter bar (hold)
END - Close Tab
PgUp - Go one Tab to Right
PgDn - Go one Tab to Left
RCtrl - Paste message to archive (press+hold) - context menu
```

▶️***To enable modified interface, you need "chrome" folder and "user.js" file*** (be careful with this file - it makes a "permanent" change to program settings = to undo changes, it is not enough to delete it, but you have to manually edit preferences in "about:config". The way to avoid this manual modification is to backup ```prefs.js``` file) ***copy into your ThunderFox profile (about:profiles)***. If you don't want to modify web content, just delete ```userContent.css``` file. If you want to return removed buttons/icons and some other small things, just delete upper "Delete me" part in ```userChrome.css``` file and all except first 5 lines in ```user.js``` file (CSS 132 / ESR+)

Firefox/Thunderbird installers can be extracted by WinRar/7-Zip and then used without installation. Profiles can be manually created and run via ***thunderfox.exe -p*** or automatically created (if it doesn't already exist) and run via (example) ***thunderfox.exe -profile "a:\000"***. Offline mode ***thunderfox.exe -offline***

Most of colors I've changed are pink (FF00A3, E20074), orange (FB7914) and in url (fdd7aa, springgreen) - they can be easily found/replaced. CSS files can be edited and tested even by your pet = data loaded from it are only temporary in RAM memory and after deleting files there is no trace of them in profile or Firefox itself

🚫disabling notifications and downloading updates - create ```updates``` file in ```C:\ProgramData\Mozilla``` or ```C:\ProgramData\MozillaXXX```. Or deny access (NTFS Permissions Tools). However, these methods may cause a bug in Thunderbird (inability to open settings and browse emails)
<br/>
🚫disabling compatibility check of profile - delete ```compatibility.ini``` file and create ```compatibility.ini``` folder. Profile may or may not be damaged, but its use will no longer be decided by someone else

⚠️ Thunderbird has a limited length of splitter (for window resizing) to avoid interfering with some icons
<br/>
<br/>
<br/>
To view images in full size (2560x1080) you can save page as ***Web page, complete*** (7MB)
<br/>
<img width="720" alt="nahled10" src="https://github.com/user-attachments/assets/370f2b52-a2f9-4f10-954d-1a90bc35adf0" />
<br/>
<br/>
<br/>
***140*** (2025-2026) - sidebar+context menu, 30+2 opened tabs (Compact 👍) - 150% DPI
<img width="1920" height="1080" alt="140-side+context-30" src="https://github.com/user-attachments/assets/40b2ecdd-a3e6-41a8-88e9-16adb8b69cf4" />
<br/>
Semi/hide/remove orange scrollbars+splitter (tabs) ```#sidebar-launcher-splitter {background-color: light-dark(#EAEAED94, #1C1B2275)!important;max-width: 0px!important;min-width: 0px!important;}```

***140*** (2025-2026) - sidebar+context menu, 15+2 opened tabs (compact 🤔) - 150% DPI
<img width="1920" height="1080" alt="140-side+context-def-15" src="https://github.com/user-attachments/assets/b3d1a71e-b2dd-4a52-9c10-74d9ff42bbd2" />

***132*** (2024) - 1-LINE - ↕️31px (72px taskbar, Win11) 150% system DPI. 1920x1080
![132-31px](https://github.com/user-attachments/assets/d1aabf83-6d4d-4a07-94c0-2ae0ec3eda4b)

***115*** (2023-2025) - 1-LINE - ↕️33px (56px taskbar, Win7) 150% system DPI. 1920x1080
![115-esr-1-line](https://github.com/user-attachments/assets/2a41bc59-5913-4142-a8f9-9e756370138f)

***140*** (2025-2026) - 150% DPI + narrow scrollbar + "mail.uidensity", 0 (Compact 👍). 1920x1080 ↕️339px
<img width="1920" height="1080" alt="tb140-339" src="https://github.com/user-attachments/assets/30d4fea9-d0b6-4343-966d-4e4abfc04cda" />

***140*** (2025-2026) - 150% DPI + narrow scrollbar + "mail.uidensity", 0 (compact 🤔). 1920x1080 ↕️616px
<img width="1920" height="1080" alt="tb140-616" src="https://github.com/user-attachments/assets/02e58374-310b-4ec5-b53e-96f659351044" />

***115*** (2023-2024) - 150% DPI + narrow scrollbar + "mail.uidensity", 0 (Compact 👍). 1920x1080 ↕️498px
![115-498](https://github.com/user-attachments/assets/a6c98f66-3714-4c15-b248-7870b80c61d4)

***115*** (2023-2024) - 150% DPI + narrow scrollbar + "mail.uidensity", 0 (compact 🤔). 1920x1080 ↕️754px
![115-754](https://github.com/user-attachments/assets/ebd35afb-c3b3-4db5-b46a-526364fd9b2e)

***119*** (2023) - 3-LINE - 1080p ↕️132px - 18,5 + 5 tabs - 150% DPI
![119 - CSS - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/48f40788-2c44-45ad-b7dd-c2d97007de59)

***119*** (2023) - DEFAULT - ↕️155px - 30 tabs - 100% DPI
![119 - default - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/bea14270-7ed3-4800-9679-c001b47e92bf)

***119*** (2023) - DEFAULT - ↕️231px - 15,5 + 5 tabs - 150% DPI
![119 - DEF - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/5b63679b-2546-4c5a-880d-5931260b8a52)

***119*** (2023) - 3-LINE - ↕️65px - 19 + 3 tabs - 150% system DPI - "find in page" bar over address bar. In this case, the entire interface fits into default "find in page" bar ⬆️😁. Pressing CTRL+F (default hotkey for searching) overlays address bar, pressing ALT+D (default hotkey for focusing address bar) overlays find in page bar. Height of find in page bar should not exceed height of bar it overlays, otherwise page will jump a few pixels when opened. And overlay only works for first bar from bottom - trying to overlay bar above will just crop bottom part of UI and make page jump again. Example in image is only possible way to use it seamlessly (overlaying bookmarks or opened tabs doesn't make sense to me = unfortunately does not work in 2-LINE - latest check FF140)
<img width="1280" alt="119 - CSS - 150% DPI4" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/7c0cbe8e-4580-491a-aa76-f9f255b9fe08">
```
/* IMPORTANT - find ".findbar-find-previous" (userChrome.css) and change "padding-left" number - example
.findbar-find-previous {padding-left: 213px!important;}
Works in FF 109/119 */
.browserContainer > findbar {-moz-box-ordinal-group: 0!important;order: -1 !important;}
.browserContainer > findbar {max-width: 700px!important;margin-top: -25px!important;} /* if web content jumps when pressing CTRL+F, the number needs to be adjusted */
.findbar-highlight, .findbar-case-sensitive, .findbar-match-diacritics, .findbar-entire-word {max-width: 10%!important;font-size: 10px !important;margin: 0px!important;margin-top: -2px!important;}
.findbar-find-status {max-width: 2000px!important;}
.findbar-label.findbar-find-status {margin-left: -100px!important;max-width: 20%!important;font-size: 10px !important;}
.findbar-find-status[status="notfound"] {margin-left: 0px!important;font-size: 13px !important;}
.findbar-container {scrollbar-width: none!important;}
.findbar-textbox {position: fixed!important;margin-top: -4px!important;} /* position of textbox */
```

***140*** (2025-2026) - 3-LINE - ↕️175px - places.xhtml - 150% DPI
<img width="1920" height="1080" alt="140-places-175" src="https://github.com/user-attachments/assets/c3ceab3c-3b09-4494-ad2c-73dbfafec94b" />

***140*** (2025-2026) - DEFAULT - ↕️559px - places.xhtml - 150% DPI
<img width="1920" height="1080" alt="140-places-559" src="https://github.com/user-attachments/assets/48e48faa-cab4-4433-ac64-18601d50e9c9" />

<br/>
<br/>
<br/>
<br/>
<br/>

## historical-comparison

***140*** - Gen2 (2025-07) - 2-LINE - ↕️67px 150% DPI
<img width="960" height="540" alt="140-1" src="https://github.com/user-attachments/assets/f3233fe1-0831-4806-a5fb-ab681365aa4d" />

***140*** (2025-2026) - DEFAULT - ↕️129px 150% DPI
<img width="960" height="540" alt="140-0" src="https://github.com/user-attachments/assets/0d92c930-21b6-46c9-bc7e-2a94bf24d478" />

***132*** (2024) - 2-LINE - ↕️64px 150% DPI. 1920x1080
![132-64px](https://github.com/user-attachments/assets/e101f381-14b8-4d72-9df5-3046e2f1453c)

***132*** (2024) - DEFAULT - ↕️85px 100% DPI. 1920x1080
<img width="960" alt="132-def-85px" src="https://github.com/user-attachments/assets/d08713d4-d854-4a2b-9d7d-f6c603dd5442">

***119*** (2023) - 2-LINE - ↕️64px 150% DPI
![119 - CSS-2-LINE - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/5a963df3-8c71-4c8a-97f1-ac99f74e270d)

***119*** (2023) - DEFAULT - ↕️85px 100% DPI
![119 - DEF-2-LINE - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/288daae3-ed5c-4165-9dc5-2ce9849f3723)

***109*** - (2023) - 2-LINE - ↕️67px 150% DPI
![109 - CSS - 150% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/151487eb-1c16-48c6-bd1d-ef37ec4f42d8)

***109*** (2023) - DEFAULT - ↕️85px 100% DPI
![109 - DEF - 100% DPI](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/56afb603-3962-4152-9518-7a9ac65129d7)

***99*** Gen1 (2023-03) - 2-LINE ↕️64px - 33,5 opened tabs - smallest tab width (browser.tabs.tabMinWidth) - 150% DPI
<img width="1280" alt="Firefox (150% DPI) - compact" src="https://user-images.githubusercontent.com/127822397/234294708-65de1f44-8723-42ad-8c16-1d44ac7aefa8.png">

***99*** (2022) - DEFAULT ↕️85px 30 opened tabs - 100% DPI
<img width="1280" alt="099 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/564f68bc-3263-41be-8790-6a68b1f2398b">

***89*** (2021) - 2-LINE ↕️61px 150% DPI
<img width="1280" alt="089 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/0e33a1bb-14d9-4d55-aba4-83536c444eca">

***89*** (2021) - DEFAULT ↕️85px 100% DPI
<img width="1280" alt="089 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/a55bcd9d-6a3f-4940-bd3d-381f5e7c0d27">

***79*** (2020) - 2-LINE ↕️61px 150% DPI
<img width="1280" alt="079 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/18e53d69-2ec5-43f1-9ec3-650ee8d0b01c">

***79*** (2020) - DEFAULT ↕️74px 100% DPI
<img width="1280" alt="079 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/edab11b7-0771-49cf-92db-eecc0369c01a">

***69*** (2019) - 2-LINE ↕️64px 150% DPI
<img width="1280" alt="069 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/8ba89a97-ad17-43c7-9fc6-b8772cb6e2c0">

***69*** (2019) - DEFAULT ↕️74px 100% DPI
<img width="1280" alt="069 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/b1ef0974-47aa-4883-88c5-18b98854cd2b">

***59*** (2018) - 2-LINE ↕️65px - opening menu bar in FF59- through ALT+arrows - 150% DPI
<img width="1280" alt="059 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/f691cfca-ae43-434e-ba8e-dbeea2447117">

***59*** (2018) - DEFAULT ↕️73px 100% DPI
<img width="1280" alt="059 - DEFAULT - 100% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/00bbb9f8-9533-406f-986e-ed7e6da151c8">

***49*** (2016) - 2-LINE ↕️68px 150% DPI
<img width="1280" alt="049 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/3c58188f-8e72-4d69-b3f9-1f24a858410f">

***49*** (2016) - DEFAULT ↕️71px 100% DPI
<img width="1280" alt="Firefox 49 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/ce717463-65f1-47c3-9206-4a3b3ffa74ab">

***39*** (2015) - 2-LINE ↕️65px 150% DPI
<img width="1280" alt="039 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/4bc30f4b-7d86-43eb-9665-ddfa4c49661c">

***39*** (2015) - DEFAULT ↕️71px 100% DPI
<img width="1280" alt="039 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/f3ebdc14-293b-4ed0-a8a9-1b0889a1e23c">

***29*** (2014) - 2-LINE ↕️64px 150% DPI
<img width="1280" alt="029 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/b6a20a17-2c82-46d6-8737-49300428d959">

***29*** (2014) - DEFAULT ↕️71px 100% DPI
![029 (100% DPI)-DEFAULT](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/21d733dd-1928-4092-8792-2681db9466b0)

***19*** (2013) - 2-LINE ↕️66px 150% DPI
<img width="1280" alt="019 - CSS3 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/d83e706a-a183-4f1f-8317-a978143ef671">

***19*** (2013) - DEFAULT ↕️63px 100% DPI
<img width="1280" alt="019 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/05739ab3-8fc7-4d90-a50d-e3c37c3e9434">

***9*** (2011) - 2-LINE ↕️64px 150% DPI
<img width="1280" alt="009 - CSS3 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/829675ee-b28d-412c-92d2-44be9ee7fb53">

***9*** (2011) - DEFAULT ↕️64px 100% DPI
<img width="1280" alt="009 (100% DPI)-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/a3751eef-a46a-4119-9277-a80e9fb056dc">

***3.5*** (2009-2011) - 2-LINE ↕️67px - "find in page" bar overlays address bar - 150% DPI
<img width="1280" alt="003 - CSS - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/4ac78e83-496f-4199-a94d-00775d24ac9e">

***3.5*** (2009-2011) - DEFAULT ↕️169px 150% DPI
<img width="1280" alt="003-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/d5262193-2ab2-432b-b1e8-13da2ffe1fa9">

***2*** (2006-2008) - 2-LINE ↕️65px 150% DPI
<img width="1280" alt="002 - CSS2 - 150% DPI" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/6e1afe69-67f8-49e6-8c9a-d6f733395606">

***2*** (2006-2008) - DEFAULT ↕️103px 100% DPI
<img width="1280" alt="Firefox 002-DEFAULT" src="https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/assets/127822397/0e703934-25f9-4689-8d99-a59bffefc6de">

***115*** (2023-2024) - 150% DPI + narrow scrollbar + "mail.uidensity", 0 (Compact 👍). 1920x1080 ↕️289px
<img width="960" alt="thunderbird289-6" src="https://github.com/user-attachments/assets/a761e348-1e7e-4d99-8fb1-34ecc26d3fdc" />

***115*** (2023-2024) - 150% DPI + narrow scrollbar + "mail.uidensity", 0 (compact 🤔). 1920x1080 ↕️521px
<img width="960" alt="thunderbird521-6" src="https://github.com/user-attachments/assets/86f4ca9a-51c2-4cd9-b160-ae86fb0a468f" />

## useful-addons-about-config

[***Enhancer for YouTube***](https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube/)
<br/>
[***YouTube Ad Auto-skipper***](https://addons.mozilla.org/en-US/firefox/addon/youtube-ad-auto-skipper/)
<br/>
[***Hide YouTube Fullscreen Controls***](https://addons.mozilla.org/en-US/firefox/addon/hide-youtube-controls/)
<br/>
[***SaveFrom.net helper***](https://addons.mozilla.org/en-US/firefox/addon/savefromnet-helper/)
<br/>
[***I don't care about cookies***](https://addons.mozilla.org/en-US/firefox/addon/i-dont-care-about-cookies/)
<br/>
[***Image Video Block***](https://addons.mozilla.org/en-US/firefox/addon/image-video-block/)
<br/>
[***Print Edit WE***](https://addons.mozilla.org/en-US/firefox/addon/print-edit-we/)
<br/>
[***Save Page WE***](https://addons.mozilla.org/en-US/firefox/addon/save-page-we/)
<br/>
[***User-Agent Switcher***](https://addons.mozilla.org/en-US/firefox/addon/uaswitcher/)
<br/>
[***Hide My IP Free***](https://addons.mozilla.org/en-US/firefox/addon/hide-my-ip-free/)
<br/>
[***Disable HTML5 Autoplay***](https://addons.mozilla.org/en-US/firefox/addon/disable-autoplay/) - issues with cloudflare, seznam.cz+cncenter.cz (profiles)
<br/>
[***Large Image Blocker***](https://addons.mozilla.org/en-US/firefox/addon/large-image-blocker/) - can save up to 100+MB per Steam page by blocking GIF videos+other unoptimized images
<br/>
[***Load Background Tabs Lazily***](https://addons.mozilla.org/en-US/firefox/addon/load-background-tabs-lazily/) - resource limiter (without it, some pages may require a refresh if they don't load within time limit) + ban limiter (DDoS attack)

***dpi***
<br/>
layout.css.devPixelsPerPx

***turning off full screen warning***
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

***disable animations (interface of program and website itself) - probably no need to be afraid of blindly toggling "animat" and "transition" preferences***
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

***a compact density option will be added to "customize toolbar" menu***
<br/>
browser.compactmode.show

***set compact density immediately by number 1***
<br/>
browser.uidensity

***disable graphical user interface "Proton"***
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

***disable request to delete settings when browser is not started for a long time***
<br/>
browser.disableResetPrompt;true

***disable query to enable DRM***
<br/>
browser.eme.ui.enabled;false

***slow Firefox startup - turn off notifications***
<br/>
browser.slowStartup.notificationDisabled

***do not turn off firefox when closing last tab***
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

***disable enforcement of signing add-ons***
<br/>
xpinstall.signatures.required;false
<br/>
security.signed_app_signatures.policy

***disable blacklisting of add-ons***
<br/>
extensions.blocklist.enabled;false

***not to allow arbitrary banning of add-ons***
<br/>
extensions.legacy.enabled;true

***do not save list of currently opened tabs to disk = reduce writing to SSD***
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

***maximum size of cached file on SSD***
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

***limiting number of firefox.exe processes***
<br/>
fission
<br/>
dom.ipc.processCount

***FPS limiter***
<br/>
layout.frame_rate

***reduce "Page Referrer" (from which webpage link was opened)***
<br/>
network.http.referer.disallowCrossSiteRelaxingDefault, true

***disable "Page Referrer". May broke some websites (steamdb.info)***
<br/>
network.http.sendRefererHeader, 0

***pretending different FF version or OS - example***
<br/>
general.useragent.override, Mozilla/5.0 (Windows NT 6.1; Win64; x64; rv:126.0) Gecko/20100101 Firefox/126.0/Yirxwl2yEK2v8lv4

***show hidden addons in about:debugging***
<br/>
devtools.aboutdebugging.showHiddenAddons

***disable PDF***
<br/>
pdfjs.disabled

***acceleration, media support***
<br/>
layers.acceleration
<br/>
dxva
<br/>
media.hardware-video
<br/>
media.wmf.dxva.d3d9.amd-pre-uvd4.disabled
<br/>
ffvpx
<br/>
opus
<br/>
flac
<br/>
ogg
<br/>
wav
<br/>
wmf
<br/>
mp4
<br/>
264
<br/>
webm
<br/>
vp9
<br/>
av1
<br/>
canvas

***image blocker***
<br/>
permissions.default.image;2

***may fix broken youtube***
<br/>
network.http.http3.enable;false

***may fix non-functional addons***
<br/>
extensions.manifestV3.enabled;	false

***tooltip delay***
<br/>
ui.tooltipDelay, 50

***if access to a particular page is forbidden for "security" reasons***
<br/>
security.tls.version.min

***disable ads in about:addons***
<br/>
extensions.htmlaboutaddons.recommendations.enabled
<br/>
extensions.getAddons.showPane

***enable browser toolbox***
user_pref("devtools.chrome.enabled", true);
<br/>
user_pref("devtools.debugger.remote-enabled", true);
<br/>
user_pref("devtools.debugger.prompt-connection", false);

***disable tab grouping***
<br/>
browser.tabs.groups.enabled

----------------------------------------------------------------------------------------------***Thunderbird***
<br/>
***disable blocked image notification***
<br/>
mailnews.message_display.disable_remote_image
<br/>
<br/>
<br/>
<br/>
<br/>
<br/>
## other

***https://github.com/topics/firefox?l=css&o=desc&s=stars***
<br/>
***https://github.com/search?q=firefox+language%3ACSS&type=repositories&l=CSS&s=stars&o=desc***
<br/>
***https://github.com/topics/thunderbird?l=css&o=desc&s=stars***
<br/>
***https://github.com/search?q=thunderbird+language%3ACSS&type=repositories&l=CSS&s=stars&o=desc***
<br/>
***https://firefoxcss-store.github.io/***
<br/>
***https://www.reddit.com/r/FirefoxCSS/***
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
***https://support.mozilla.org/en-US/kb/keyboard-shortcuts-thunderbird***
<br/>
***https://www.mozilla.org/en-US/firefox/releases/***
<br/>
***https://www.thunderbird.net/en-US/thunderbird/releases/***
<br/>
***https://whattrainisitnow.com/calendar/***

Language packs (addons) are in ```xpi``` folder
<br/>
***https://ftp.mozilla.org/pub/firefox/releases/***
<br/>
***https://ftp.mozilla.org/pub/fenix/releases/***
<br/>
***https://ftp.mozilla.org/pub/thunderbird/releases/***
<br/>
***https://mozilla.github.io/policy-templates/***
<br/>
***https://caniuse.com/***
<br/>
***https://www.deviceinfo.me/***
<br/>
***https://explore.whatismybrowser.com/useragents/explore/software_name/firefox/***
<br/>
***https://html5test.com/***
<br/>
***https://georgebastock.github.io/CSS-Animation-Test/***
<br/>
***https://www.w3schools.com/css/css3_transitions.asp***
<br/>
***https://www.w3schools.com/css/css3_shadows.asp***

***89*** - Gen0 (2021-12) 150% DPI
<img width="1280" alt="0" src="https://github.com/user-attachments/assets/dfce3ad3-8359-45c9-9b32-66687f75309d">

***99*** - Gen0+ (2023-01) 150% DPI
<img width="1280" alt="0+" src="https://github.com/user-attachments/assets/77ef5ce3-cfa2-4566-9602-c645eccb4cc5">

Customization (userChrome.css)
<img width="1280" alt="Customization" src="https://user-images.githubusercontent.com/127822397/235342097-4f9103a9-7211-4d33-b17b-600c438eee2f.png">

----------------------------------------------------------------------------------------------***suggestions for improvements***
<br/>
-remove titles/checkboxes in "find in page" bar and replace them with buttons/icons (for addressbar+findbar overlay)
<br/>
-renaming bookmarks directly (long/short right mouse click)
<br/>
-tabs with play/pause button and hotkey (replace useless volume button)
<br/>
-combine "Edit Folder/Bookmark" in context menu into a single entry at one specific position (properties in FF79-)
<br/>
-popup status bar around mouse cursor
<br/>
-add-ons in "Customize Toolbar" menu
<br/>
-decrease mouse vert sensitivity when cursor approaches left/right sides of bookmarks (folders)
<br/>
-custom colours of folders for quick orientation (bookmarks)
<br/>
-javaScript CPU/GPU resource limiter (rotating ad can use entire CPU core regardless of its frequency)
<br/>
-remove items from address bar (long/short right mouse click)
<br/>
-in places.xhtml show paths to items (searching)
<br/>
-better use downloads area (places.xhtml) bug - ```.allDownloadsListBox {display: flex!important;flex-wrap: wrap!important;}``` (140 userContent.css)
<br/>
-show download % + time in places.xhtml tab name
<br/>
-option switch tabs with hotkeys in places.xhtml (like FF89-)
<br/>
-custom tabs color (by domain), automatic grouping
<br/>
-move current tab at e.g. position 2 (CTRL+2)
<br/>
-tab switching by domain (custom hotkeys)
<br/>
-option to open a new panel in a new exclusive EXE process (this will prevent possible freezing/crashing of tabs in a shared process)
<br/>
-hide ```https://www.``` in address bar
<br/>
-separate audio/video cache from normal cache. What's the point of current setup where important cache data is overwritten by useless video that also reduces SSD lifetime? Constantly modifying NTFS permissions for cache folder is not very comfortable...
<br/>
-smooth scrolling (pixel steps) of the page after pressing e.g. CTRL+left click
<br/>
-sorting in about:config
<br/>
-it is not possible to redirect "safebrowsing" folder from the ramdisk to SSD (NTFS links), which leads to constant downloading of the same data every time the profile is deleted and copied again (ramdisk)
<br/>
-if file "c:\Users\XXX\AppData\Local\Mozilla" exists, it is not possible to start FF (~v19+)
<br/>
***Thunderbird***
<br/>
-long click functions - e.g. for saving attachment(s)
<br/>
-hide some attachment sizes (b/kb)
<br/>
-keep user's icon color when selected - #folderTree:focus-within li.selected > .container > .icon {--icon-color: currentColor !important;} - works if this style is unchecked (115)
<br/>
-better use of the "Message Header Pane" space - partially solved ("from"). [This addon does it quite well](https://addons.thunderbird.net/en-us/thunderbird/addon/compact-headers/)
<br/>
-disable+hide some days in calendar
<br/>
-remove "tree view" (done), colored first character instead + global option of collapsing/expanding threads + remove arrows
<br/>
-scrollable top bar (like tabs), use empty side/status bar space

android - holding (some UI) automatically performs assigned action (close tab, open bookmarks, open link in new tab and switch to it, ...), disable double tap to select text, buttons on one side for one hand (landscape mode), remove notification when opening/closing tab + other minor UI adjustments - e.g.
<br/>
🤦android (5.5" 960x480, fullscreen) vs CSS - really only a 2,7 tabs can fit on the screen?🤦
<br/>
<img width="480" alt="android" src="https://github.com/user-attachments/assets/f301be89-32f6-4977-890f-4b925d19e29e" />
<img width="480" alt="androidnext" src="https://github.com/user-attachments/assets/3ed67b54-5d2d-4f99-b788-69a988d41704" />

***FF*** Win 2006+ ```1-64``` ```43``` ```52``` ```64``` ```68``` ```73``` ```78``` ```84``` ```89``` ```99``` ```115``` (internet explorer offline 2004-2006)
<br/>
***TB*** Win 2016+ ```38``` ```45-68``` ```78``` ```91``` ```99``` ```109``` ```115```
<br/>
***FF*** android 2024+ ```132``` (chrome ```71``` 2021-2024)
