Pro zapnutí upraveného rozhraní je tøeba složku "chrome" a soubor "user.js" (u tohoto souboru pozor - provádí "trvalou" zmìnu v nastavení programu = pro navrácení zmìn zpìt ho nestaèí jenom smazat, ale musí se ruènì upravit pøedvolby v "about:config". Zpùsob, jak se vyhnout této ruèní úpravì je záloha souboru "prefs.js") nakopírovat do vašeho Firefox profilu





Chyby a pøípadné návrhy na vylepšení (userChrome.css)
-lišta s otevøenými panely mùže být na výšku nesmyslnì velká - problém souvisí s velikostí "titlebar" ve Windows - zmenšit se mùže pøes program "Winaero Tweaker" podnabídka "Window Title Bars". Mùže se také hodit posunutí lišty o pár pixelù podle potøeby - vyhledat øádek "otevøené panely - posunutí". Pokud nechcete mìnit systémovou velikost "titlebar", tak se mùže hodit "otevøené panely - zmenšit výšku lišty" - v tomto pøípadì ale mùže dojít k zásadnímu narušení fullscreen režimu (F11). U nìkterých skinù také mùže být mnou ne úplnì ideálnì vynucená barva urèitých prvkù rozhraní - ale vzhledem k tomu, že rozhraní cílím na svoje skiny, tak koho to zajímá
-pøi doèasném zobrazení hlavní nabídky (ALT) není možné kliknout na ikony "minimalizovat/obnovit/zavøít"
-vyskakovací panel "najít na stránce" by chtìlo odstranit a jeho funkce zabudovat do adresního øádku (CTRL+F pro pøepnutí režimu)
-po vzoru "Total Commander" by chtìlo pøidat funkci pravého tlaèítka myši navíc (kliknutí / kliknutí+podržení)

















about:config
NASTAVENÍ PØEDVOLEB SE DÌLÁ PØES STRÁNKU about:config ( vyhledávejte pøedvolby jako napø. "media.autoplay.enabled" a ne v celém formátu vèetnì pøepínaèe "media.autoplay.enabled;false", který uvádím jenom nìkde a èasto jen pro orientaci )

VŠE DÌLÁTE NA VLASTNÍ NEBEZPEÈÍ, ALE ZMÌNÌNÉ POLOŽKY SE DAJÍ SNADNO PØEPNOUT NA VÝCHOZÍ NASTAVENÍ ( TUÈNÌ ZVÝRAZNÌNÉ JSOU ZMÌNÌNÉ )
NÌKTERÉ PØEDVOLBY JSOU MNOHO LET STARÉ A MOŽNÁ V NOVÝCH VERZÍCH FIREFOX NEEXISTUJÍ / NEFUNGUJÍ / JSOU ZBYTEÈNÉ
* pokud v "about:config" chybí napøíklad pøedvolba na výchozí pøiblížení PDF souborù ( pdfjs.defaultZoomValue ), tak jí mùžete vytvoøit. Pokud vytvoøení jakékoli nové pøedvolby nebude mít vámi požadovaný efekt, tak jí nezapomeòte zase smazat




;dpi - tøeba 1.75
layout.css.devPixelsPerPx

;poèet položek v adresním øádku
browser.urlbar.maxRichResults

;vypnutí hlášky režimu celé obrazovky
full-screen-api.warning.timeout;0

;schovat øádek "návrhy od Firefoxu" v adresním øádku
browser.urlbar.groupLabels.enabled;false

;vypnout dotaz na smazání nastavení pøi dlouhém nespuštìní prohlížeèe
browser.disableResetPrompt;true

;vypnout dotaz na zapnutí DRM
browser.eme.ui.enabled;false

;pomalé zapínání Firefox - vypnout upozornìní
browser.slowStartup.notificationDisabled

;vypnutí vybledlého písma v adresním øádku
browser.urlbar.formatting.enabled;false

;výchozí pøiblížení *.pdf souborù
pdfjs.defaultZoomValue;page-width

;hledání - vybarvení
ui.textSelectBackgroundAttention;#ff0000
ui.textHighlightBackground;#ff0000
ui.textHighlightForeground;#ff0000

;vypnutí èerného posuvníku (ideálnì na èerném pozadí)
widget.disable-dark-scrollbar

;velikost posuvníkù
widget.non-native-theme.scrollbar.size
widget.non-native-theme.win.scrollbar.use-system-size
widget.non-native-theme.scrollbar.size.override

;vypnutí popiskù pøi najetí myší na záložky
browser.chrome.toolbar_tips

;nevypínat firefox pøi zavøení posledního panelu
browser.tabs.closeWindowWithLastTab;false

;zobrazení nových oken pouze v panelech
browser.link.open_newwindow.restriction;0

;dotaz o poloze
geo.enabled

; vypnout upozornìní "nezabezpeèené pøihlášení"
security.insecure_field_warning.contextual.enabled;false

;ctrl+shift+j
devtools.chrome.enabled;true

;vypnutí update
app.update.doorhang;false

;skrytí ikony èteèka
reader.parse-on-load.enabled;false

;šedá barva "nový panel"
browser.display.background_color;#eeeeee

;v nabídce "nastavení tlaèítek a lišt" pøibyde možnost kompaktní velikosti
browser.compactmode.show

;nastavit kompaktní velikost okamžitì èíslem 1
browser.uidensity

;vypnout grafické uživatelské rozhraní "Proton"
browser.proton.enabled

;vypnout autoplay
media.autoplay.enabled;false
media.autoplay.allow-muted;false

;vypnout animace - asi netøeba se bát naslepo pøepínaèe "animat" a "transition" povypínat
browser.fullscreen.animate;false
browser.tabs.animate;false
image.animation_mode;none

;zapnout podporu pøehrávání *.webm
media.mediasource.webm.enabled

;vypnout vynucení podepsání doplòkù
xpinstall.signatures.required;false

;zakázat vypnutí "blacklist" doplòkù 
extensions.blocklist.enabled;false

;neumožnit svévolné zakazování doplòkù
extensions.legacy.enabled;true

;neukládat na disk seznam právì otevøených panelù = snížit zápis na SSD
browser.sessionstore.resume_from_crash;false

;nevytváøet zálohy záložek
browser.bookmarks.max_backups;0

;zakázání automatického obnovování stránek
accessibility.blockautorefresh;true

;maximální velikost cache na SSD
browser.cache.disk.capacity;180000000

;maximální velikost nacachovaného souboru na HDD 
browser.cache.disk.max_entry_size

;izolování cache
browser.cache.cache_isolation;true

;èasový limit pøipojení
network.http.connection-timeout

;vypnout  náhledy pøi pøetahování panelù/záložek
nglayout.enable_drag_images;false

;firefox.exe - priorita "normální"
dom.ipc.processPriorityManager.enabled;false

;omezení poètu firefox.exe procesù ( výhoda je ve zrychlení a menším nárokùm na CPU+RAM a nevýhoda ve zhoršené bezpeènosti )
fission.autostart;false

;minimální šíøka otevøených panelù
browser.tabs.tabMinWidth






Užiteèné doplòky

Avast Online Security - reputace stránek
Disable HTML5 Autoplay - vypnutí autoplay a pøednaèítání videí
Enhancer for YouTube
Hide YouTube Fullscreen Controls - možné nastavit toto chování - pøi pohybu myši do strany se skryjí veškeré popisky, interface pøehrávaèe a vyskakovací reklamy = zobrazit èisté video
I don't care about cookies
Image Video Block
Large Image Blocker - uživatelsky nastavitelná maximální velikost obrázkù/gif atd. Co pøekroèí stanovenou velikost se nebude stahovat ani zobrazovat
Load Background Tabs Lazily - možnost otevøít tøeba 100 záložek najednou a stránky se budou naèítat postupnì
Print Edit WE + Save Page WE - editace + uložení stránky do jednoho souboru
SaveFrom.net helper - ukládání videí z youtube atd - možnost stáhnout pouze zvukovou stopu
YouTube Ad Auto-skipper
Firefox Color - vlastní skin
Flagfox - umístìní serverù a zobrazení vlajky státu



* alternativa nového okna "knihovna stránek" ( CTRL+SHIFT+H/O/J ) je nový panel na adrese chrome://browser/content/places/places.xhtml
* vypnutí instalování aktualizací - zbavit se souboru "updater.exe". Vypnutí upozornìní, že nelze stáhnout aktualizaci - zakázat pøístup ke složce "C:\ProgramData\Mozilla..."
* vypnutí kontroly kompatibility profilu a pøípadnì zakázání jeho použití - smazat obsah "compatibility.ini" a nastavit na "read only"



https://www.reddit.com/r/FirefoxCSS/
https://www.userchrome.org/
https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html