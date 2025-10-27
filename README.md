# Mein macOS Setup

---

## Inspiration

* [macOS Setup Guide](http://sourabhbajaj.com/mac-setup/)
* [macOS Monterey: Setting up a Mac for Development](https://www.taniarascia.com/setting-up-a-brand-new-mac-for-development/)
* [Mac Setup for Web Development 2022](https://www.robinwieruch.de/mac-setup-web-development/)

## macOS Systemeinstellungen

### Netzwerk

* Firewall: aktivieren

### Allgemein

#### Info

* Name > Gerätename anpassen

### Bedienungshilfen

* Zoomen
  * Tastaturkurzbefehle zum Zoomen verwenden: aktivieren
  * Zoomstil: "Bild-in-Bild" (durch die Tastenkombination CTRL + ALT wird eine Lupe eingeblendet)
  * Zoomstil Optionen > Fensterposition: Mauszeiger folgen
* Anzeige
  * Transparenz reduzieren: aktivieren | [OSX Daily Artikel](http://osxdaily.com/2016/01/02/disable-transparency-effects-mac-os-x/)

### Erscheinugnsbild

* Dunkel
* Einfärbung des Hintergrunds in Fenstern erlauben: deaktivieren
* Rollbalken einblenden: Beim scrollen

### Kontrollzentrum

* Ton > Immer in Menüleiste anzeigen
* Batterie
  * In Menüleiste anzeigen: aktivieren
  * Im Kontrollzentrum anzeigen: aktivieren
  * Prozent anzeigen: aktivieren
* Alles weitere nach Badarf

### Ton

* Beim Starten Ton abspielen: deaktivieren
* Beim Ändern der Lautstärke Ton abspielen: aktivieren

### Bildschirmzeit

* aktivieren

### Spotlight

* Spotlight > Suchergebnisse > Alles deaktivieren

### Datenschutz & Sicherheit

* FileVault: aktivieren

### Schreibtisch & Dock

* **Screenshot vorhanden**
* Größe: eher klein
* Vergrößerung aktivieren
* Position: unten
* Fenster hinter Programmsymbol im Dock ablegen: aktivieren
* Dock automatisch ein- und ausblenden: aktivieren
* Öffnen von Programmen animieren: deaktivieren
* Zuletzt verwendete Programme im Dock anzeigen: deaktivieren
* Fenster beim Beenden einer App schließen: deaktivieren
* Aktive Ecken > alles deaktiviren

### Displays

* Auflösung: Skaliert > Mehr Fläche auswählen

### Hintergrundbild

* nach Bedarf anpassen

### Bildschirmschoner

* nach Bedarf anpassen

### Batterie

* Stromsparmodus > Nur im Batteriebetrieb

### Sperrbildschirm

* Zeiten für Bildschirmschoner und Display abdunkeln nach Bedarf einstellen
* Merkhilfe für Passwörter anzeigen: aktivieren

...

### Tastatur

* Tastaturnavigation: aktivieren
* Kurzbefehle
  * Tastatur > Fokus in nächstes Fenster: `cmd` + `<`
  * Spotlight
    * Spotlight-Suche anzeigen: deaktivieren
    * Finder-Suchfenster anzeigen: deaktivieren
* Texteingabe > Eingabequellen bearbeiten
  * Rechtschreibung automatische Korrektur: deaktivieren
  * Wörter automatisch groß schreiben: deaktivieren
  * Punkt mit doppeltem Leerzeichen hinzufügen: deaktivieren

### Trackpad

* Zeigen und Klicken
  * Zeigerbewegung: Geschwindigkeit auf ~ 90% stellen
  * Sekundärklick: Mit zwei Fingern klicken oder tippen
  * Klick durch Tippen: aktivieren
* Scrollen und Zoomen > Alles aktivieren
* Weitere Gesten
  * Mission Control: Mit drei Fingern aufwärts streichen
  * App-Exposè: Mit drei Fingern abwärts streichen

## Dock

* Unwichtige Apps raus löschen (aus dem Doc entfernen)
* Übrig bleibt nur:
  * Finder
  * Systemeinstellungen
  * Safari

## Finder

### Einstellungen

* Allgemein
  * Diese Objekte auf dem Schreibtisch anzeigen: Alles deaktivieren
  * Neue Finder-Fenster zeigen: Schreibtisch
* Seitenleiste
  * Objekte zusätzlich aktivieren:
    * [Benutzername]
    * [Gerät]
    * Festplatten
  * Objekte deaktivieren:
    * Tags
* Erweitert
  * Alle Dateinnamemsuffixe einblenden: aktivieren

### Weitere Anpassungen

* Favoritenleiste Reihenfolge anpassen:
  * Schreibtisch
  * Zuletzt benutzt
  * AirDrop
  * Programme
  * Benutzerordner
  * Dokumente
  * Bilder
  * Sites
  * Downloads
* Rechtsklick im Finder > Darstellungsoptionen einblenden > Sortiert nach: Art
* Finder Menü-Leiste > Darstellung > Pfadleiste einblenden
* Finder Menü-Leiste > Darstellung > Statusleiste einblenden
* Befehle im Terminal ausführen
  * Versteckte Dateien anzeigen > `defaults write com.apple.finder AppleShowAllFiles YES`
  * Library Ordner anzeigen > `chflags nohidden ~/Library`

## Homebrew

* [Homebrew](https://brew.sh/) installieren (der Paketmanager für macOS)
  * `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
  * 🛑 Next steps am Ende der Installtion im Terminal beachten 🛑 // PATH anpassen [Link mit Infos](https://sourabhbajaj.com/mac-setup/Homebrew/)
  * Checkup mit `brew update` und `brew doctor`

## Tools & Programme

* Apps mit Homebrew installieren: `brew install google-chrome firefox the-unarchiver vlc iterm2 appcleaner`

* [Raycast](https://raycast.com/) `brew install raycast`
* [Rocket Typist](https://www.witt-software.com/rockettypist/)
* [BitWarden - Passwort-Manager macOS App](https://bitwarden.com/download/) `brew install bitwarden`
* [MarkEdit for Markdown - Markdown-Editor](https://apps.apple.com/app/id1669953820) `brew install markedit`
* [Maccy - Clipboard manager for macOS](https://maccy.app/) `brew install maccy`
* [Tiles - The window manager for macOS](https://www.sempliva.com/tiles/) `brew install tiles`
* [Shottr - Screenshot Tool mit Scrollshot](https://shottr.cc/) `brew install shottr`
* [RainDrop.io - Bookmark Manager](https://raindrop.io/download)
* [Chat GPT](https://openai.com/de-DE/chatgpt/download/)
* [7-Zip - Datei Archivierung](https://7-zip.org/) `brew install sevenzip`

### Tools & Programme - Direkt im App Store unter Account zu finden

* [Plain Text Editor - Text-Editor](https://sindresorhus.com/plain-text-editor)
* [Dropover - Drag & Drop Tool](https://apps.apple.com/de/app/dropover-m%C3%BChelose-drag-drop/id1355679052?mt=12)

### Google Apps / Websites als App installieren

* GMail
* Kalender
* Drive
* Tasks
* Keep (Notizen)
* Youtube Music
* Youtube
* Gemini

### Nice to have

* [Latest - Software Update Checker](https://max.codes/latest/) `brew install latest`
* [NameChanger](https://mrrsoftware.com/namechanger/) `brew install namechanger`
* [Gemini 2 - Der intelligente Duplikatscanner](https://macpaw.com/de/gemini)
* [Bildschirmschoner Fliqlo - Flip clock screensaver](https://fliqlo.com/screensaver/)
* [SquirrelDisk - Speicherplatzanalyse](https://github.com/adileo/squirreldisk)
* [NearDrop - An unofficial Google Nearby Share app for macOS (AirDrop Klon)](https://github.com/grishka/NearDrop)
* [AppLite- Make managing third party applications](https://aerolite.dev/applite)
* [Cakebrew - The Mac App for Homebrew](https://www.cakebrew.com/)
* [AnyDesk - Remote Desktop Software](https://anydesk.com/de/downloads/mac-os)
* [WhatsApp](https://www.whatsapp.com/download?lang=de_DE)

### Nice to have - Developer Tools

* Apps mit Homebrew installieren: `brew install imageoptim sequel-ace tower visual-studio-code github microsoft-office`

* [SnippetsLab - Snippet Manager](https://apps.apple.com/de/app/snippetslab/id1006087419?mt=12)
* [Chrome Canary](https://www.google.de/chrome/browser/canary.html)
* [FileZilla](https://filezilla-project.org/download.php?type=client)
* [Pika - Color Picker](https://superhighfives.com/pika) `brew install pika`
* [Android File Transfer](https://www.android.com/filetransfer/)
* [Virtual Box](https://www.virtualbox.org/wiki/Downloads) (Nicht mit Apple Silicon Chip kompatibel!)

### Nice to have - Media Tools

* [Miro Video Converter](http://www.mirovideoconverter.com/)
* [Free Video Converter](https://itunes.apple.com/de/app/free-video-converter/id464195348?mt=12)
* [LosslessCut - Simple, cross platform video editor](https://github.com/mifi/lossless-cut)

### Hardware-spezifisch

* [Logitech Options+ App - Tastatur-Einstellungen](https://www.logitech.com/de-de/software/logi-options-plus.html)
* [Logitech Logi Bolt App - Pairing-Einstellungen](https://support.logi.com/hc/de/articles/4418089333655)
* [Elgato Stream Deck](https://www.elgato.com/de/de/s/downloads)

### Chrome Erweiterungen

* [Google Übersetzer](https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb)
* [Pesticide for Chrome](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh)
* [Validity](https://chrome.google.com/webstore/detail/validity/bbicmjjbohdfglopkidebfccilipgeif)
* [Full Page Screen Capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
* [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
* [RainDrop.io - Bookmark Manager](https://chromewebstore.google.com/detail/raindropio/ldgfbffkinooeloadekpmfoklnobpien)
* AdBlock

### MacOS Quick Look (Datei Vorschau) erweitern

* ~~[All-in-one Quick Look plugin](https://github.com/samuelmeuli/glance)~~

## Developer Setup

### Basics

* Ab macOS Catalina ist [zsh](https://www.zsh.org/) die Standard Shell
* [Oh-My-Zsh](http://ohmyz.sh/)
  * Installation via curl `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
  * Weitere Einstellungen im Abschnitt ganz unten
  * [Weitere Details & Infos](https://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
* Node via [NVM - Node Version Manager](https://github.com/nvm-sh/nvm)
  * Installation via curl `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash`
  * Install the latest version with `nvm install node`
  * Install the latest LTS version with `nvm install --lts`
  * [nvm is broken after I installing oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/issues/5543)
* `brew install yarn`

### NPM Installationen

* Gulp
  * `yarn global add gulp`
* Browser Sync
  * `yarn global add browser-sync`
* MJML
  * `yarn global add mjml`
* NPM Check Updates
  * [https://www.npmjs.com/package/npm-check-updates](https://www.npmjs.com/package/npm-check-updates)
  * `yarn global add npm-check-updates`

### Fonts

* [Hack | A typeface designed for source code / Patched fonts for Powerline users.](https://github.com/powerline/fonts/tree/master/Hack)

### Git SSH Keys erstellen

* [Anleitung Github](https://help.github.com/articles/generating-ssh-keys/)
* [Anleitung Bitbucket](https://confluence.atlassian.com/bitbucket/set-up-an-ssh-key-728138079.html)

### Websites Ordner erstellen

* Im Benutzer-Profil einen Ordner `Sites` erstellen. Dieser bekommt dann automatisch das Icon.
* Darin eine .htaccess mit folgendem Inhalt erstellen `Options +Indexes`

### SMB Verbindung - Signierung deaktivieren

* [Turn off packet signing for SMB 2 and SMB 3 connections](https://support.apple.com/en-us/HT205926)

## Programm Einstellungen

### Shottr

* General
  * Window Screenshot Background > Solid Color (#404448)
  * Screenshot folder: Desktop
  * Resize retina screenshots: deaktivieren
  * Autostart: Launch at startup: aktivieren
  * After screenshot: Show & Copy: aktivieren
  * After Area Crop, show: Thumbnail
* Hotkeys
  * Full screenshot: `cmd` + `Shift` + `3`
  * Area screenshot: `cmd` + `Shift` + `4`
  * Active window screenshot: `cmd` + `Shift` + `5`
  * Instant Text/OR Recognition: `cmd` + `Shift` + `O`
* Advanced
  * Primary OCR Language: German
  * OCR line breaks: aktivieren
  * Action when hiding with ESC: Copy Image & Save Image: aktivieren
  * Confirmation style: none
* License
  * License Key: [Hier Lizenz eingeben]

### Rocket Typist

* Allgemein > Automatisch nach Login starten: aktivieren
* Allgemein > Baustein-Tastaturkürzel: `cmd` + `Shift` + `B`

### SnippetsLab

* Sync > iCloud Sync: aktivieren

### TextEdit

* Einstellungen > Neues Dokument
  * Format: Reiner Text
  * Schrift: Menlo Regular, 18

### Chrome

* Vor Beenden waren aktivieren > Menü Chrome > "Vor Beenden waren" aktivieren
* Erweiterte Einstellungen > Downloads Pfad ändern auf "Schreibtisch"
* Developer-Tools > Settings > Devices > folgende Custom Devies anlegen
  * Laptop FullHD mit 1920x1080
  * Laptop XL mit 1520x800
  * Laptop LG mit 1280x800
  * Laptop MD mit 1024x768

### Raycast

* Settings können aus bestehendem Setup exportiert und neu importiert werden
* Für den Hyperkey (Settings > Advanced) muss in den macOS Systemeinstellungen > Datenschutz & Sicherheit > Bedienungshilfen > Raycast aktiviert werden

### Tiles

* General > Startup: Launch Tiles at login: aktivieren

### Maccy

* Beim Anmelden starten: aktivieren
* Automatisch nach Updates suchen: aktivieren
* Öffnen mit: `cmd` + `Shift` + `V`
* Verhalten: Automatisch einfügen: aktivieren
* Verhalten: Einfügen ohne Formatierung: aktivieren
* Speicher > Sichern: Dateien: deaktivieren
* Erscheinungsbild > Anwendungssymbole anzeigen: aktivieren

### MarkEdit

* Assistant > Format Files: Insert final newline: aktivieren
* Assistant > Format Files: Trim trailing whitespace: aktivieren

### Logitech Options+

* Tastatur-Einstellungen
  * F4 > Desktop anzeigen/verbergen

### iTerm2 + ZSH

* Theme Neu 2021: [Sindre Sorhus' Snazzy color theme.](https://github.com/sindresorhus/iterm2-snazzy)
* Cobalt2 Theme von Wes Bos [Anleitung](https://github.com/wesbos/Cobalt2-iterm)
  * Powerline Schritt übersprungen
  * Patched Hack Font Download siehe oben
* [trash - Dateien & Ordner 'in Papierkorb' löschen](https://github.com/sindresorhus/trash)
* [Set the iTerm tab title to the current directory, not full path](https://gist.github.com/phette23/5270658)
* [Settings to emojify and prettify your terminal (iTerm2 & ZSH)](https://www.stefanjudis.com/blog/declutter-emojify-and-prettify-your-iterm2-terminal/)

zsh-autosuggestions: Dieses Plugin schlägt Befehle basierend auf deinem Verlauf vor, während du tippst.
`git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions`

### FileZilla

* Servermanager Einträge importieren
* Einstellungen > Übertragungen > Maximale Anzahl gleichzeitiger Übertragungen: 6
* Einstellungen > Übertragungen > FTP: Dateitypen > Standard-Übertragungstyp: Binär
* Einstellungen > Bearbeiten von Dateien > Benutzerdefinierten Editor verwednden > `"/Applications/Visual Studio Code.app"`

### MAMP

* View Mode: Expert View
* Settings
  * General
    * Keyboard Shortcut: deaktivieren
    * Show Status in Menubar: aktivieren
    * Dont use blue elephant: aktivieren
  * Server
    * Launch GroupStart Servers > when starting MAMP Pro
* Ports & Users
  * Button Klick: Set ports to 80, 81, …
