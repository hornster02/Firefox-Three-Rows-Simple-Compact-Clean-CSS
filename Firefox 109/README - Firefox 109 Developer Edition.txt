Pro zapnut� upraven�ho rozhran� je t�eba slo�ku "chrome" a soubor "user.js" (u tohoto souboru pozor - prov�d� "trvalou" zm�nu v nastaven� programu = pro navr�cen� zm�n zp�t ho nesta�� jenom smazat, ale mus� se ru�n� upravit p�edvolby v "about:config". Zp�sob, jak se vyhnout t�to ru�n� �prav� je z�loha souboru "prefs.js") nakop�rovat do va�eho Firefox profilu





Chyby a p��padn� n�vrhy na vylep�en� (userChrome.css)
-li�ta s otev�en�mi panely m��e b�t na v��ku nesmysln� velk� - probl�m souvis� s velikost� "titlebar" ve Windows - zmen�it se m��e p�es program "Winaero Tweaker" podnab�dka "Window Title Bars". M��e se tak� hodit posunut� li�ty o p�r pixel� podle pot�eby - vyhledat ��dek "otev�en� panely - posunut�". Pokud nechcete m�nit syst�movou velikost "titlebar", tak se m��e hodit "otev�en� panely - zmen�it v��ku li�ty" - v tomto p��pad� ale m��e doj�t k z�sadn�mu naru�en� fullscreen re�imu (F11). U n�kter�ch skin� tak� m��e b�t mnou ne �pln� ide�ln� vynucen� barva ur�it�ch prvk� rozhran� - ale vzhledem k tomu, �e rozhran� c�l�m na svoje skiny, tak koho to zaj�m�
-p�i do�asn�m zobrazen� hlavn� nab�dky (ALT) nen� mo�n� kliknout na ikony "minimalizovat/obnovit/zav��t"
-vyskakovac� panel "naj�t na str�nce" by cht�lo odstranit a jeho funkce zabudovat do adresn�ho ��dku (CTRL+F pro p�epnut� re�imu)
-po vzoru "Total Commander" by cht�lo p�idat funkci prav�ho tla��tka my�i nav�c (kliknut� / kliknut�+podr�en�)

















about:config
NASTAVEN� P�EDVOLEB SE D�L� P�ES STR�NKU about:config ( vyhled�vejte p�edvolby jako nap�. "media.autoplay.enabled" a ne v cel�m form�tu v�etn� p�ep�na�e "media.autoplay.enabled;false", kter� uv�d�m jenom n�kde a �asto jen pro orientaci )

V�E D�L�TE NA VLASTN� NEBEZPE��, ALE ZM�N�N� POLO�KY SE DAJ� SNADNO P�EPNOUT NA V�CHOZ� NASTAVEN� ( TU�N� ZV�RAZN�N� JSOU ZM�N�N� )
N�KTER� P�EDVOLBY JSOU MNOHO LET STAR� A MO�N� V NOV�CH VERZ�CH FIREFOX NEEXISTUJ� / NEFUNGUJ� / JSOU ZBYTE�N�
* pokud v "about:config" chyb� nap��klad p�edvolba na v�choz� p�ibl�en� PDF soubor� ( pdfjs.defaultZoomValue ), tak j� m��ete vytvo�it. Pokud vytvo�en� jak�koli nov� p�edvolby nebude m�t v�mi po�adovan� efekt, tak j� nezapome�te zase smazat




;dpi - t�eba 1.75
layout.css.devPixelsPerPx

;po�et polo�ek v adresn�m ��dku
browser.urlbar.maxRichResults

;vypnut� hl�ky re�imu cel� obrazovky
full-screen-api.warning.timeout;0

;schovat ��dek "n�vrhy od Firefoxu" v adresn�m ��dku
browser.urlbar.groupLabels.enabled;false

;vypnout dotaz na smaz�n� nastaven� p�i dlouh�m nespu�t�n� prohl�e�e
browser.disableResetPrompt;true

;vypnout dotaz na zapnut� DRM
browser.eme.ui.enabled;false

;pomal� zap�n�n� Firefox - vypnout upozorn�n�
browser.slowStartup.notificationDisabled

;vypnut� vybledl�ho p�sma v adresn�m ��dku
browser.urlbar.formatting.enabled;false

;v�choz� p�ibl�en� *.pdf soubor�
pdfjs.defaultZoomValue;page-width

;hled�n� - vybarven�
ui.textSelectBackgroundAttention;#ff0000
ui.textHighlightBackground;#ff0000
ui.textHighlightForeground;#ff0000

;vypnut� �ern�ho posuvn�ku (ide�ln� na �ern�m pozad�)
widget.disable-dark-scrollbar

;velikost posuvn�k�
widget.non-native-theme.scrollbar.size
widget.non-native-theme.win.scrollbar.use-system-size
widget.non-native-theme.scrollbar.size.override

;vypnut� popisk� p�i najet� my�� na z�lo�ky
browser.chrome.toolbar_tips

;nevyp�nat firefox p�i zav�en� posledn�ho panelu
browser.tabs.closeWindowWithLastTab;false

;zobrazen� nov�ch oken pouze v panelech
browser.link.open_newwindow.restriction;0

;dotaz o poloze
geo.enabled

; vypnout upozorn�n� "nezabezpe�en� p�ihl�en�"
security.insecure_field_warning.contextual.enabled;false

;ctrl+shift+j
devtools.chrome.enabled;true

;vypnut� update
app.update.doorhang;false

;skryt� ikony �te�ka
reader.parse-on-load.enabled;false

;�ed� barva "nov� panel"
browser.display.background_color;#eeeeee

;v nab�dce "nastaven� tla��tek a li�t" p�ibyde mo�nost kompaktn� velikosti
browser.compactmode.show

;nastavit kompaktn� velikost okam�it� ��slem 1
browser.uidensity

;vypnout grafick� u�ivatelsk� rozhran� "Proton"
browser.proton.enabled

;vypnout autoplay
media.autoplay.enabled;false
media.autoplay.allow-muted;false

;vypnout animace - asi net�eba se b�t naslepo p�ep�na�e "animat" a "transition" povyp�nat
browser.fullscreen.animate;false
browser.tabs.animate;false
image.animation_mode;none

;zapnout podporu p�ehr�v�n� *.webm
media.mediasource.webm.enabled

;vypnout vynucen� podeps�n� dopl�k�
xpinstall.signatures.required;false

;zak�zat vypnut� "blacklist" dopl�k� 
extensions.blocklist.enabled;false

;neumo�nit sv�voln� zakazov�n� dopl�k�
extensions.legacy.enabled;true

;neukl�dat na disk seznam pr�v� otev�en�ch panel� = sn�it z�pis na SSD
browser.sessionstore.resume_from_crash;false

;nevytv��et z�lohy z�lo�ek
browser.bookmarks.max_backups;0

;zak�z�n� automatick�ho obnovov�n� str�nek
accessibility.blockautorefresh;true

;maxim�ln� velikost cache na SSD
browser.cache.disk.capacity;180000000

;maxim�ln� velikost nacachovan�ho souboru na HDD 
browser.cache.disk.max_entry_size

;izolov�n� cache
browser.cache.cache_isolation;true

;�asov� limit p�ipojen�
network.http.connection-timeout

;vypnout  n�hledy p�i p�etahov�n� panel�/z�lo�ek
nglayout.enable_drag_images;false

;firefox.exe - priorita "norm�ln�"
dom.ipc.processPriorityManager.enabled;false

;omezen� po�tu firefox.exe proces� ( v�hoda je ve zrychlen� a men��m n�rok�m na CPU+RAM a nev�hoda ve zhor�en� bezpe�nosti )
fission.autostart;false

;minim�ln� ���ka otev�en�ch panel�
browser.tabs.tabMinWidth






U�ite�n� dopl�ky

Avast Online Security - reputace str�nek
Disable HTML5 Autoplay - vypnut� autoplay a p�edna��t�n� vide�
Enhancer for YouTube
Hide YouTube Fullscreen Controls - mo�n� nastavit toto chov�n� - p�i pohybu my�i do strany se skryj� ve�ker� popisky, interface p�ehr�va�e a vyskakovac� reklamy = zobrazit �ist� video
I don't care about cookies
Image Video Block
Large Image Blocker - u�ivatelsky nastaviteln� maxim�ln� velikost obr�zk�/gif atd. Co p�ekro�� stanovenou velikost se nebude stahovat ani zobrazovat
Load Background Tabs Lazily - mo�nost otev��t t�eba 100 z�lo�ek najednou a str�nky se budou na��tat postupn�
Print Edit WE + Save Page WE - editace + ulo�en� str�nky do jednoho souboru
SaveFrom.net helper - ukl�d�n� vide� z youtube atd - mo�nost st�hnout pouze zvukovou stopu
YouTube Ad Auto-skipper
Firefox Color - vlastn� skin
Flagfox - um�st�n� server� a zobrazen� vlajky st�tu



* alternativa nov�ho okna "knihovna str�nek" ( CTRL+SHIFT+H/O/J ) je nov� panel na adrese chrome://browser/content/places/places.xhtml
* vypnut� instalov�n� aktualizac� - zbavit se souboru "updater.exe". Vypnut� upozorn�n�, �e nelze st�hnout aktualizaci - zak�zat p��stup ke slo�ce "C:\ProgramData\Mozilla..."
* vypnut� kontroly kompatibility profilu a p��padn� zak�z�n� jeho pou�it� - smazat obsah "compatibility.ini" a nastavit na "read only"



https://www.reddit.com/r/FirefoxCSS/
https://www.userchrome.org/
https://firefox-source-docs.mozilla.org/devtools-user/browser_toolbox/index.html