
2023-2026

⬇️ [Historical comparison](#historical-comparison) / [Useful addons + about:config](#useful-addons-about-config) / [Other](#other) ⬇️

***CSS Calendar*** - FF153 (beta - 1.Aug.2026 /// final - 15.Aug.2026), TB - skip 1 ESR release + 1 month (2027)

***android - [📥 desktop mode as default + fullscreen](https://github.com/hornster02/hornster02/raw/main/android.rar)***
<br/>

***Firefox CSS - [📥 140](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/140-esr(9-140+)_gen2.rar)⠀[📥 themes (light)](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/theme.rar)⠀[📥 Autohotkey v1.1 ⬇️](https://github.com/hornster02/Firefox-Three-Rows-Simple-Compact-Clean-CSS/raw/main/script.rar)***

```
ESC (hold/double) - Page with/out style
Tab (hold, double) - switching between last 3 tabs
~ (hold/double) - Show/hide vertical "List All Tabs" "folder" (button must not be removed)
F2 - Find Previous (searchbar)
INS - Focus Address bar (press) / Address bar history (hold)
Del (hold) - copy URL. Activate bottom Notepad++, keywait CTRL+V and activate bottom Firefox is disabled
Home - New Tab (press) / Address bar bookmarks (hold)
END - Close Tab
PgUp - Go one Tab to Right (press) / Address bar tabs (hold)
PgDn - Go one Tab to Left

F1 - Bookmarks (press) / History (hold) / Downloaded (double) [places.xhtml, open in tab 1, focus on search =
address bar+download button+side bar alternative] + "Enter" for opening in new tab (press/hold), CZ/EN FF

YoutubeFullscreenDumbAdSkipper (numenter - Mute+show player ui /// numdot - unMute+skip ad /// 2560/1920x1080)

Default hotkeys
F3 - Find Next (searchbar)
MButton (close tab / open bookmark(s))
Alt+F4 (close FF)
Win+arrows (minimize/maximize/restore window)
CTRL+TAB (ALT+TAB for FF)
CTRL+UP/DOWN (page up/down)
Tab, Shift+Tab (UI elements switch)
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

▶️***To enable modified interface, you need "chrome" folder and "user.js" file*** (be careful with this file - it makes a "permanent" change to program settings = to undo changes, it is not enough to delete it, but you have to manually edit preferences in "about:config". Way to avoid this manual modification is to backup ```prefs.js``` file) ***copy into your ThunderFox profile (about:profiles)***. If you don't want to modify web content (first global row may cause issues on some websites - Google login doesn't work without playing animation on first attempt - F5, Steam images do not repeat endlessly when hovering over them with mouse, ...), just delete ```userContent.css``` file. If you want to return removed buttons/icons and some other small things, just delete upper "Delete me" part in ```userChrome.css``` file and all except first 5 lines in ```user.js``` file (CSS 132 / ESR+)

Firefox/Thunderbird installers can be extracted by WinRar/7-Zip and then used without installation. Profiles can be manually created and run via ***thunderfox.exe -p*** or automatically created (if it doesn't already exist) and run via (example) ***thunderfox.exe -profile "a:\000"***. Offline mode ***thunderfox.exe -offline***

most of colors I've changed are pink (FF00A3, E20074), orange (FB7914) and in url (fdd7aa, springgreen) - they can be easily found/replaced. CSS files can be edited and tested even by your pet = data loaded from it are only temporary in RAM memory and after deleting files there is no trace of them in profile or Firefox itself

🚫disabling downloading updates - ```updates``` in ```C:\ProgramData\Mozilla``` or ```C:\Users\XXX\AppData\Local\Mozilla``` (restrict access). However, these method can cause a bug in Thunderbird (inability to open settings and browse emails)

🚫disabling compatibility check of profile - ```compatibility.ini``` (restrict access). Profile may or may not be damaged, but its use will no longer be decided by someone else

CSS FF59- opening menu bar through ALT+arrows (2-LINE)

FF117+ is working again in Win7 ***[kernel1](https://github.com/YuZhouRen86/VxKex-NEXT) [2](https://github.com/i486/VxKex) [3](https://github.com/vxiiduu/VxKex) or [FF](https://github.com/e3kskoy7wqk/Firefox-for-windows-7)*** [without ```user_pref("media.rdd-wav.enabled", false);``` (prefs.js) FF140 may not run in Win7]

CSS FF140 (sidebar tabs) semi/hide/remove orange scrollbars+splitter ```#sidebar-launcher-splitter {background-color: light-dark(#EAEAED94, #1C1B2275)!important;max-width: 0px!important;min-width: 0px!important;}```

CSS TB115+ has a limited length of splitter (for window resizing) to avoid interfering with some icons

userContent.css - static web for testing (can cause issues/break = some webpages can't even display text without animations) ```* {animation-duration: unset !important; animation: unset !important; transform: unset !important; rotate: unset !important;}```

Feel free to report CSS issues (from 115+) either as an "Issue" or via email = it seems that number of features/GUI elements in FF/TB is growing, and it’s possible that I’m not even aware of some of them + I’m using old Win7 2009. If some GUIs haven’t been edited by me for compactness, it means they’re unimportant to me, and I might also create bugs by doing so. FFCSS Gen1 (2-132) is very buggy
<br/>
CSS created in Win11 2021 (virtual machine) - FF119, FF132
<br/>
Versions I used -
<br/>
***FF*** Win 2006+ ```1-64``` ```43``` ```52``` ```64``` ```68``` ```73``` ```78``` ```84``` ***89 CSS*** ```99``` ```115``` ```140``` (internet explorer offline 2004-2006)
<br/>
***TB*** Win 2016+ ```38``` ```45-68``` ```78``` ```91``` ```99``` ```109``` ***115 CSS*** ```140```
<br/>
***FF*** android 2024+ ```132``` (chrome ```71``` 2021-2024)

***FF49 (2016)*** ```general.useragent.override``` -
<br/>
youtube, google drive (2026) ```Mozilla/5.0 (PlayStation 5 3.03/SmartTV) AppleWebKit/605.1.15 (KHTML, like Gecko)```
<br/>
facebook (2026) ```Mozilla/5.0 (Macintosh; Intel Mac OS X 10_15_7) AppleWebKit/605.1.15 (KHTML, like Gecko) Version/17.0 Safari/605.1.15```
<br/>
<br/>
<br/>
To view images in full size (50+, 1920x1080, earlier 2560x1080) you can save page as ***Web page, complete*** (7MB)
<br/>
<img width="720" height="278" alt="nahled11" src="https://github.com/user-attachments/assets/880af04d-b05d-4d1b-9ad4-7fe32d6fd314" />

***140*** (2025-2026) - sidebar+context menu, 30+2 opened tabs (Compact 👍) - 150% DPI
<img width="1920" height="1080" alt="140-side+context-30" src="https://github.com/user-attachments/assets/40b2ecdd-a3e6-41a8-88e9-16adb8b69cf4" />

***140*** (2025-2026) - sidebar+context menu, 15+2 opened tabs (compact 🤔) - 150% DPI
<img width="1920" height="1080" alt="140-side+context-def-15" src="https://github.com/user-attachments/assets/b3d1a71e-b2dd-4a52-9c10-74d9ff42bbd2" />

***132*** (2024) - 1-LINE - ↕️31px (72px taskbar, Win11) 150% system DPI. 1920x1080
![132-31px](https://github.com/user-attachments/assets/d1aabf83-6d4d-4a07-94c0-2ae0ec3eda4b)

***115*** (2023-2026) - 1-LINE - ↕️33px (56px taskbar, Win7) 150% system DPI. 1920x1080
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

***119*** (2023) - 3-LINE - ↕️65px - 19 + 3 tabs - 150% system DPI - "find in page" bar over address bar. In this case, the entire interface fits into default "find in page" bar ⬆️😁. Pressing CTRL+F (default hotkey for searching) overlays address bar, pressing ALT+D (default hotkey for focusing address bar) overlays find in page bar. Height of find in page bar should not exceed height of bar it overlays, otherwise page will jump a few pixels when opened. And overlay only works for first bar from bottom - trying to overlay bar above will just crop bottom part of UI and make page jump again. Example in image is only possible way to use it seamlessly (overlaying bookmarks or opened tabs doesn't make sense to me = unfortunately does not work in 2-LINE - last check FF140)
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

***99*** Gen1 (2023-03) - 2-LINE ↕️64px - 33,5 opened tabs - 150% DPI
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

***59*** (2018) - 2-LINE ↕️65px - 150% DPI
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

[***Enhancer for YouTube***](https://www.mrfdev.com/enhancer-for-youtube)
<br/>
[***YouTube Ad Auto-skipper***](https://github.com/squgeim/yt-ad-autoskipper)
<br/>
[***Hide YouTube Fullscreen Controls***](https://github.com/nralbrecht/youtube-hide-controls)
<br/>
[***YouTube Scrollable Fullscreen***](https://addons.mozilla.org/en-GB/firefox/addon/youtube-scrollable-fullscreen/)
<br/>
[***YourCodecs***](https://github.com/undecV/YourCodecs) - blocking AVC can fix broken youtube (An error occurred. Please try again LATER) - Windows without audio/video codecs
<br/>
[***SaveFrom.net helper***](https://savefrom.net)
<br/>
[***Image Video Block***](https://github.com/tiborbarsi/image-video-block-browser-addon)
<br/>
[***Disable HTML5 Autoplay***](https://addons.mozilla.org/en-US/firefox/addon/disable-autoplay/) - issues with cloudflare (seznam.cz+cncenter.cz+pcgw)
<br/>
[***Large Image Blocker***](https://addons.mozilla.org/en-US/firefox/addon/large-image-blocker/) - can save up to 100+MB per Steam page by blocking GIF videos+other unoptimized images
<br/>
[***I still don't care about cookies***](https://github.com/OhMyGuus/I-Still-Dont-Care-About-Cookies)
<br/>
[***Print Edit WE***](https://addons.mozilla.org/en-US/firefox/addon/print-edit-we/)
<br/>
[***Save Page WE***](https://addons.mozilla.org/en-US/firefox/addon/save-page-we/)
<br/>
[***User-Agent Switcher***](https://gitlab.com/ntninja/user-agent-switcher)
<br/>
[***Hide My IP Free***](https://www.hidemyip.com/)
<br/>
[***QRCode Scanner***](https://github.com/laobubu/QRScaner)
<br/>
[***Load Background Tabs Lazily***](https://addons.mozilla.org/en-US/firefox/addon/load-background-tabs-lazily/) - resource limiter (without it, some pages may require a refresh if they don't load within time limit) + ban limiter (DDoS attack)
<br/>
[***android new tabs in foreground***](https://addons.mozilla.org/en-US/firefox/addon/android_new_tabs_in_foreground/)

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

***save interval = reduce writing to SSD***
<br/>
browser.sessionstore.interval

***do not create bookmarks backups***
<br/>
browser.bookmarks.max_backups;0

***disabling automatic page refresh***
<br/>
accessibility.blockautorefresh;true

***maximum cache size on SSD (increase 1GB limit)***
<br/>
browser.cache.disk.capacity
<br/>
browser.cache.disk.smart_size.enabled;false

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

***suspend+throttling (background) tabs (+download function)***
<br/>
thrott
<br/>
suspend
<br/>
connections

***FPS limiter***
<br/>
layout.frame_rate
<br/>
gfx.display.max-frame-rate

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
media.hardware-video-decoding.enabled
<br/>
media.hardware-video-decoding.force-enabled
<br/>
```media*enable```
<br/>
```media*disable```
<br/>
```audio*enable```
<br/>
264
<br/>
gmp
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
mp4 - can fix broken youtube (An error occurred. Please try again LATER), Windows without audio/video codecs, without mp4 support can be increased bitrate
<br/>
webm
<br/>
vp9
<br/>
av1
<br/>
canvas

***disable endless downloading of "tmpaddon*" (~14MB per session) to TEMP folder***
<br/>
media.gmp-provider.enabled
<br/>
media.gmp-widedevine.enabled
<br/>
media.gmp-widevinecdm.enabled
<br/>
media.gmp.decoder.enabled

***image blocker***
<br/>
permissions.default.image;2

***can fix broken youtube***
<br/>
network.http.http3.enable;false

***can fix non-functional addons***
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

***disable picture in picture***
<br/>
picture-in-picture

***disable translation query***
<br/>
browser.translations.enable

***disable about:config warning***
<br/>
user_pref("browser.aboutConfig.showWarning", false);
<br/>
user_pref("general.warnOnAboutConfig", false);

***enable specific theme***
<br/>
user_pref("extensions.activeThemeID", "firefox-compact-light@mozilla.org");
<br/>
user_pref("devtools.theme", "light");

***disable def browser check***
<br/>
user_pref("browser.shell.checkDefaultBrowser", false);

***disable close tabs warning***
<br/>
user_pref("browser.tabs.warnOnClose", false);

***enable sidebar***
<br/>
sidebar.revamp

***switch to opened tab***
<br/>
browser.tabs.loadInBackground

***zoom 30-%***
<br/>
zoom.minPercent

--------------------------------------------------------------------------------------------***Thunderbird***
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
<br/>
***https://connect.mozilla.org/t5/ideas/idb-p/ideas/tab/most-kudoed***

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
***https://test-ipv6.com***
<br/>
***https://www.google.com/intl/en/ipv6/statistics.html***
<br/>
***https://browserleaks.com/***
<br/>
***https://georgebastock.github.io/CSS-Animation-Test/***
<br/>
***https://www.w3schools.com/css/css3_transitions.asp***
<br/>
***https://www.w3schools.com/css/css3_shadows.asp***
<br/>
***https://gsap.com/js/speed.html***

***89*** - Gen0 (2021-12) 150% DPI
<img width="1280" alt="0" src="https://github.com/user-attachments/assets/dfce3ad3-8359-45c9-9b32-66687f75309d">

***99*** - Gen0+ (2023-01) 150% DPI
<img width="1280" alt="0+" src="https://github.com/user-attachments/assets/77ef5ce3-cfa2-4566-9602-c645eccb4cc5">

Customization (userChrome.css)
<img width="1280" alt="Customization" src="https://user-images.githubusercontent.com/127822397/235342097-4f9103a9-7211-4d33-b17b-600c438eee2f.png">

--------------------------------------------------------------------------------------------***suggestions for improvements***
<br/>
-remove titles/checkboxes in "find in page" bar and replace them with buttons/icons (for addressbar+findbar overlay)
<br/>
-renaming bookmarks directly (long/short right mouse click)
<br/>
-tabs with play/pause button and hotkey (replace useless volume button)
<br/>
-combine "Edit Folder/Bookmark" in context menu into a single entry at one specific position (properties in ~FF79-)
<br/>
-popup status bar around mouse cursor
<br/>
-add-ons in "Customize Toolbar" menu
<br/>
-decrease mouse vert sensitivity when cursor approaches left/right sides of bookmarks (folders)
<br/>
-custom colours of folders for quick orientation (bookmarks)
<br/>
-javaScript CPU/GPU resource limiter (rotating ad can use entire CPU core regardless of its frequency), pause javaScript/animation ~5s after page is loaded (without reloading)
<br/>
-remove items from address bar (long/short right mouse click)
<br/>
-in places.xhtml show paths to items (searching)
<br/>
-better use downloads area (places.xhtml) bug - ```.allDownloadsListBox {display: flex!important;flex-wrap: wrap!important;}``` (140 userContent.css)
<br/>
-show download % + time in places.xhtml tab name
<br/>
-option switch tabs with hotkeys from places.xhtml (like ~FF89-)
<br/>
-custom tabs color (by domain), automatic grouping
<br/>
-move current tab at e.g. position 2 (CTRL+2)
<br/>
-tab switching by domain (custom hotkeys)
<br/>
-option to open a new panel in a new exclusive EXE process (prevent possible freezing/crashing of tabs in a shared process)
<br/>
-if all tabs in background are suspended, then have option to manually select tabs that will never be suspended
<br/>
-hide ```https://www.``` in address bar
<br/>
-separate audio/video cache from normal cache. What's the point of current setup where important cache data is overwritten by useless video that also reduces SSD lifetime? Constantly modifying NTFS permissions for cache folder (or using second FF profile with media support enabled) is not very comfortable...
<br/>
-sorting/selecting in about:config, hide changed prefs
<br/>
-drag tabs without animation (~FF9- style)
<br/>
-hor tab bar scrolling with animation (~FF99- style, "ui.prefersReducedMotion"), custom roll steps, custom animation speed
<br/>
-UI overlay fullscreen (autohide, video+pdf+...)
<br/>
-it is not possible to redirect "safebrowsing" folder from the ramdisk to SSD (NTFS links), which leads to constant downloading of the same data every time the profile is deleted and copied again (ramdisk)
<br/>
-if file "c:\Users\XXX\AppData\Local\Mozilla" exists, it is not possible to start FF (~v19+)
<br/>
-if file "datareporting" exists (in profile), FF freezes on start (~v119-132)
<br/>
-hide "new tab" labels (empty space is more visible)
<br/>
-bandwith limiter (browsing,download,upload)
<br/>
-reset addon settings
<br/>
-stream (download) audio only option, auto stop streaming video if FF/tab is in background (keep audio)
<br/>
-addressbar - "-" character as search exclude (like Google search and others)
<br/>
-custom cache write delays (reduce writes to SSD)
<br/>
-browser toolbox - reset changes button, pin styles button
<br/>
-"Copy URL" in context menus (bookmarks + tabs)
<br/>
-latest closed tabs list (long click to "List All Tabs" button)
<br/>
-drag&drop between multiple FF?
<br/>
-auto accept all Untrusted Certificates?
<br/>
-regular expressions (searching)
<br/>
-open vertical list of tabs by RButton+Wheel (release buttons = open selected tab) = like Notepad++
<br/>
-backup restore profile (android)
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
-remove "tree view" (done, CSS), colored first character instead? + global option of collapsing/expanding threads + remove arrows?
<br/>
-scrollable top bar (like tabs), use empty side/status bar space

android - holding (some UI) automatically performs assigned action (close tab, open bookmarks, open link in new tab and switch to it, ...), disable double tap to select text, buttons on one side for one (left) hand (landscape mode), remove notification when opening/closing tab + other minor UI adjustments - e.g.
<br/>
🤦android (5.5" 960x480, fullscreen) vs CSS - really only a 2,7 tabs can fit on the screen?🤦
<br/>
<img width="480" alt="android" src="https://github.com/user-attachments/assets/f301be89-32f6-4977-890f-4b925d19e29e" />
<img width="480" alt="androidnext" src="https://github.com/user-attachments/assets/3ed67b54-5d2d-4f99-b788-69a988d41704" />

***Chyby webu*** -
<br/>
mbank.cz - CTRL+C/V je zakázáno (pro umělé navýšení chybovosti+prodloužení procesu je nutné ručně přepisovat částky a pro potvrzení platby i náhodné texty) - přepnout stránku na "bez stylu" a zkopírovat text a ten vložit AHK skriptem (CTRL+SHIFT+V) ```^+v::SendRaw %clipboard%```

komunitni-preklady.org/ostatni-cestiny - stránka nejde uložit, vykresluje se pouze viditelná část - přepnout stránku na "bez stylu" /// nebo snížit DPI hluboko pod 1 + 1% velikost stránky + přepnout rozlišení obrazovky na výšku /// nebo použít Save Page WE a nastavit automatické zmenšení stránky před uložením

web.archive.org - stránka nejde zachytit (PCGW,sbazar) - na konec url přidat ```?noredirect=1``` (po pár hodinách po zachycení ale stejně může dojít ke smazání záznamu)

fanatical.com - nejde (klikat) vložit zboží do košíku a procházet historii objednávek atd. = nastavit PS5 User-Agent (addon "User-Agent Switcher"). (S největší pravděpodobností může být problém v nějaké změněné předvolbě v about:config)

myabandonware.com - nejde klikat na odkazy = přidat vyjímku "I still don't care about cookies"

mapy.com - problémy s nevykreslováním - šedé obdélníky = zkontrolovat oprávnění cache složky

datoid.cz - blokace některých stránek u operátora O2 se dá obejít zvýšením "Zapnout DNS over HTTPS pomocí:"

war-forum.net (hlavní stránka) - nekonečné stahování XML souboru (chat)

nekonečný download plnou rychlostí - zřejmě pokud jsou v FF zakázány audio/video kodeky (nebo pokud chybí ty výchozí ve Win?), tak na některých serverech
<br/>
kurzy.cz - pscontent.playstream.media/manualUpload/f557xr5ocim66afifc/flickstree_video.mp4
<br/>
w3schools.com - cdn.viously.com/video/3TXPgqkObK6/1-w240.webp
<br/>
může dojít k brutálnímu bugu, kdy se místo přehrávání videoreklamy budou donekonečna (pokud uživatel nedostane ban na přehrávání reklam) stahovat/zahazovat části video souboru. Za 1 den je možné propálit stovky GB (1200GB SIM karta za 3000,- může být teoreticky jednou reklamou do 2 dnů vyčerpána). Jediné mě známé řešení je použít addon typu "Image Video Block" + "Disable HTML5 Autoplay" kteří jakékoli stahování utnou

aukro.cz (opotřebení SSD) - může docházet k podivným zápisům do "storage\default\https+++aukro.cz\cache\morgue\" = 1 otočení kolečkem myši + pauza + opakovat = ~110MB zápis + ~110MB zápis + ...

***Website issues*** -
<br/>
mbank.cz - CTRL+C/V is disabled (to artificially increase error rate and prolong process, it is necessary to manually rewrite amounts and random texts to confirm payment) - switch page to "no style" and copy text and paste it with AHK script (CTRL+SHIFT+V) ```^+v::SendRaw %clipboard%```

komunitni-preklady.org/ostatni-cestiny - page cannot be saved, only visible part is rendered - switch page to "no style" /// or reduce DPI below 1 + 1% of page size + switch screen resolution to portrait /// or use Save Page WE and set automatic page reduction before saving

web.archive.org - page cannot be captured (PCGW,sbazar) - add ```?noredirect=1``` to end of URL (however, record may still be deleted a few hours after capture)

fanatical.com - unable to add items to cart, view order history, etc. = set PS5 User-Agent (addon "User-Agent Switcher"). (Most likely, issue may be related to a modified preference in about:config)

myabandonware.com - links cannot be clicked = add exception "I still don't care about cookies"

mapy.com - problems with rendering - gray rectangles = check cache folder permission

datoid.cz - blocking of certain websites by operator O2 can be circumvented by increasing "Enable DNS over HTTPS using:"

war-forum.net (homepage) - endless downloading of XML file (chat)

endless download at full speed - apparently, if audio/video codecs are disabled in FF (or if default ones in Win are missing?), then on some servers
<br/>
kurzy.cz - pscontent.playstream.media/manualUpload/f557xr5ocim66afifc/flickstree_video.mp4
<br/>
w3schools.com - cdn.viously.com/video/3TXPgqkObK6/1-w240.webp
<br/>
may be a brutal bug where instead of playing video ads, video parts of file will be downloaded/discarded endlessly (unless user is banned from playing ads). Hundreds of GB can be used up in a single day (a 1200GB SIM card costing 120 EUR can theoretically be used up by a single ad within two days). Only solution I know of is to use an add-on such as "Image Video Block" + "Disable HTML5 Autoplay" which will stop any downloading

aukro.cz (SSD wear) - strange writes to "storage\default\https+++aukro.cz\cache\morgue\" may occur = 1 mouse wheel + pause + repeat = ~110MB write + ~110MB write + ...
