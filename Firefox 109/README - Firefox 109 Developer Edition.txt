Pro zapnutí upraveného rozhraní je třeba složku "chrome" a soubor "user.js" (u tohoto souboru pozor - provádí "trvalou" změnu v nastavení programu = pro navrácení změn zpět ho nestačí jenom smazat, ale musí se ručně upravit předvolby v "about:config". Způsob, jak se vyhnout této ruční úpravě je záloha souboru "prefs.js") nakopírovat do vašeho Firefox profilu





Chyby a případné návrhy na vylepšení (userChrome.css)
-lišta s otevřenými panely může být na výšku nesmyslně velká - problém souvisí s velikostí "titlebar" ve Windows - zmenšit se může přes program "Winaero Tweaker" podnabídka "Window Title Bars". Může se také hodit posunutí lišty o pár pixelů podle potřeby - vyhledat řádek "otevřené panely - posunutí". Pokud nechcete měnit systémovou velikost "titlebar", tak se může hodit "otevřené panely - zmenšit výšku lišty" - v tomto případě ale může dojít k zásadnímu narušení fullscreen režimu (F11). U některých skinů také může být mnou ne úplně ideálně vynucená barva určitých prvků rozhraní - ale vzhledem k tomu, že rozhraní cílím na svoje skiny, tak koho to zajímá
-při dočasném zobrazení hlavní nabídky (ALT) není možné kliknout na ikony "minimalizovat/obnovit/zavřít"
-vyskakovací panel "najít na stránce" by chtělo odstranit a jeho funkce zabudovat do adresního řádku (CTRL+F pro přepnutí režimu)
-po vzoru "Total Commander" by chtělo přidat funkci pravého tlačítka myši navíc (kliknutí / kliknutí+podržení)

















about:config
NASTAVENÍ PŘEDVOLEB SE DĚLÁ PŘES STRÁNKU about:config ( vyhledávejte předvolby jako např. "media.autoplay.enabled" a ne v celém formátu včetně přepínače "media.autoplay.enabled;false", který uvádím jenom někde a často jen pro orientaci )

VŠE DĚLÁTE NA VLASTNÍ NEBEZPEČÍ, ALE ZMĚNĚNÉ POLOŽKY SE DAJÍ SNADNO PŘEPNOUT NA VÝCHOZÍ NASTAVENÍ ( TUČNĚ ZVÝRAZNĚNÉ JSOU ZMĚNĚNÉ )
NĚKTERÉ PŘEDVOLBY JSOU MNOHO LET STARÉ A MOŽNÁ V NOVÝCH VERZÍCH FIREFOX NEEXISTUJÍ / NEFUNGUJÍ / JSOU ZBYTEČNÉ
* pokud v "about:config" chybí například předvolba na výchozí přiblížení PDF souborů ( pdfjs.defaultZoomValue ), tak jí můžete vytvořit. Pokud vytvoření jakékoli nové předvolby nebude mít vámi požadovaný efekt, tak jí nezapomeňte zase smazat




;dpi - třeba 1.75
layout.css.devPixelsPerPx

;počet položek v adresním řádku
browser.urlbar.maxRichResults

;vypnutí hlášky režimu celé obrazovky
full-screen-api.warning.timeout;0

;schovat řádek "návrhy od Firefoxu" v adresním řádku
browser.urlbar.groupLabels.enabled;false

;vypnout dotaz na smazání nastavení při dlouhém nespuštění prohlížeče
browser.disableResetPrompt;true

;vypnout dotaz na zapnutí DRM
browser.eme.ui.enabled;false

;pomalé zapínání Firefox - vypnout upozornění
browser.slowStartup.notificationDisabled

;vypnutí vybledlého písma v adresním řádku
browser.urlbar.formatting.enabled;false

;výchozí přiblížení *.pdf souborů
pdfjs.defaultZoomValue;page-width

;hledání - vybarvení
ui.textSelectBackgroundAttention;#ff0000
ui.textHighlightBackground;#ff0000
ui.textHighlightForeground;#ff0000

;vypnutí černého posuvníku (ideálně na černém pozadí)
widget.disable-dark-scrollbar

;velikost posuvníků
widget.non-native-theme.scrollbar.size
widget.non-native-theme.win.scrollbar.use-system-size
widget.non-native-theme.scrollbar.size.override

;vypnutí popisků při najetí myší na záložky
browser.chrome.toolbar_tips

;nevypínat firefox při zavření posledního panelu
browser.tabs.closeWindowWithLastTab;false

;zobrazení nových oken pouze v panelech
browser.link.open_newwindow.restriction;0

;dotaz o poloze
geo.enabled

; vypnout upozornění "nezabezpečené přihlášení"
security.insecure_field_warning.contextual.enabled;false

;ctrl+shift+j
devtools.chrome.enabled;true

;vypnutí update
app.update.doorhang;false

;skrytí ikony čtečka
reader.parse-on-load.enabled;false

;šedá barva "nový panel"
browser.display.background_color;#eeeeee

;v nabídce "nastavení tlačítek a lišt" přibyde možnost kompaktní velikosti
browser.compactmode.show

;nastavit kompaktní velikost okamžitě číslem 1
browser.uidensity

;vypnout grafické uživatelské rozhraní "Proton"
browser.proton.enabled

;vypnout autoplay
media.autoplay.enabled;false
media.autoplay.allow-muted;false

;vypnout animace - asi netřeba se bát naslepo přepínače "animat" a "transition" povypínat
browser.fullscreen.animate;false
browser.tabs.animate;false
image.animation_mode;none

;zapnout podporu přehrávání *.webm
media.mediasource.webm.enabled

;vypnout vynucení podepsání doplňků
xpinstall.signatures.required;false

;zakázat vypnutí "blacklist" doplňků 
extensions.blocklist.enabled;false

;neumožnit svévolné zakazování doplňků
extensions.legacy.enabled;true

;neukládat na disk seznam právě otevřených panelů = snížit zápis na SSD
browser.sessionstore.resume_from_crash;false

;nevytvářet zálohy záložek
browser.bookmarks.max_backups;0

;zakázání automatického obnovování stránek
accessibility.blockautorefresh;true

;maximální velikost cache na SSD
browser.cache.disk.capacity;180000000

;maximální velikost nacachovaného souboru na HDD 
browser.cache.disk.max_entry_size

;izolování cache
browser.cache.cache_isolation;true

;časový limit připojení
network.http.connection-timeout

;vypnout  náhledy při přetahování panelů/záložek
nglayout.enable_drag_images;false

;firefox.exe - priorita "normální"
dom.ipc.processPriorityManager.enabled;false

;omezení počtu firefox.exe procesů ( výhoda je ve zrychlení a menším nárokům na CPU+RAM a nevýhoda ve zhoršené bezpečnosti )
fission.autostart;false

;minimální šířka otevřených panelů
browser.tabs.tabMinWidth






Užitečné doplňky

Avast Online Security - reputace stránek
Disable HTML5 Autoplay - vypnutí autoplay a přednačítání videí
Enhancer for YouTube
Hide YouTube Fullscreen Controls - možné nastavit toto chování - při pohybu myši do strany se skryjí veškeré popisky, interface přehrávače a vyskakovací reklamy = zobrazit čisté video
I don't care about cookies
Image Video Block
Large Image Blocker - uživatelsky nastavitelná maximální velikost obrázků/gif atd. Co překročí stanovenou velikost se nebude stahovat ani zobrazovat
Load Background Tabs Lazily - možnost otevřít třeba 100 záložek najednou a stránky se budou načítat postupně
Print Edit WE + Save Page WE - editace + uložení stránky do jednoho souboru
SaveFrom.net helper - ukládání videí z youtube atd - možnost stáhnout pouze zvukovou stopu
YouTube Ad Auto-skipper
Firefox Color - vlastní skin
Flagfox - umístění serverů a zobrazení vlajky státu



* alternativa nového okna "knihovna stránek" ( CTRL+SHIFT+H/O/J ) je nový panel na adrese chrome://browser/content/places/places.xhtml
* vypnutí instalování aktualizací - zbavit se souboru "updater.exe". Vypnutí upozornění, že nelze stáhnout aktualizaci - zakázat přístup ke složce "C:\ProgramData\Mozilla..."
* vypnutí kontroly kompatibility profilu a případně zakázání jeho použití - smazat obsah "compatibility.ini" a nastavit na "read only"



https://www.reddit.com/r/FirefoxCSS/
https://www.userchrome.org/
https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html
