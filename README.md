# Mein OS X Setup

---

## Inspiration

* [macOS Setup Guide](http://sourabhbajaj.com/mac-setup/)
* [macOS Monterey: Setting up a Mac for Development](https://www.taniarascia.com/setting-up-a-brand-new-mac-for-development/)
* [Mac Setup for Web Development 2022](https://www.robinwieruch.de/mac-setup-web-development/)

## macOS Systemeinstellungen

### Netzwerk
* Firewall: aktivieren

### Ton
* Beim Starten Ton abspielen: deaktivieren
* Beim Ändern der Lautstärke Ton abspielen: aktivieren

### Bildschirmzeit
* aktivieren

### Allgemein
#### Info
* Name > Gerätename anpassen

### Erscheinugnsbild
* Dunkel
* Einfärbung des Hintergrunds in Fenstern erlauben: deaktivieren
* Rollbalken einblenden: Beim scrollen

### Bedienungshilfen
* Zoomen
  * Tastaturkurzbefehle zum Zoomen verwenden: aktivieren
  * Zoomstil: "Bild-in-Bild" (durch die Tastenkombination CTRL + ALT wird eine Lupe eingeblendet)
  * Zoomstil Optionen > Fensterposition: Mauszeiger folgen
* Anzeige
  * Transparenz reduzieren: aktivieren | [Link](http://osxdaily.com/2016/01/02/disable-transparency-effects-mac-os-x/)

### Kontrollzentrum
* Ton > Immer in Menüleiste anzeigen
* Batterie
  * In Menüleiste anzeigen: aktivieren
  * Im Kontrollzentrum anzeigen: aktivieren
  * Prozent anzeigen: aktivieren
* Alles weitere nach Badarf

### Siri & Spotlight
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
  * Zeigerbewegung: Geschwindigkeit auf ~ 75% stellen
  * Sekundärklick: Mit zwei Fingern klicken oder tippen
  * Klick durch Tippen: aktivieren
* Scrollen und Zoomen > Alles aktivieren
* Weitere Gesten
  * App-Exposè: Mit drei Fingern abwärts streichen


## Dock
* Unwichtige Apps raus löschen (aus dem Doc entfernen)
* Übrig bleibt nur:
  * Finder
  * Systemeinstellungen
  * Safari


## Finder
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

Rechtsklick im Finder > Darstellungsoptionen einblenden
* Sortiert nach: Art

Finder Menü-Leiste > Darstellung
* Pfadleiste einblenden
* Statusleiste einblenden

Befehle im Terminal ausführen
* Versteckte Dateien anzeigen > `defaults write com.apple.finder AppleShowAllFiles YES`
* Library Ordner anzeigen > `chflags nohidden ~/Library`

## Basics

* Homebrew installieren
  * `/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
  * Next steps am Ende beachten // PATH anpassen [Link mit Infos](https://sourabhbajaj.com/mac-setup/Homebrew/)
  * Checkup mit `brew update` und `brew doctor`

## Tools & Programme

* Apps mit Homebrew installieren
  * `brew install google-chrome firefox evernote dropbox spotify the-unarchiver vlc authy imageoptim iterm2 sequel-ace appcleaner tower visual-studio-code github microsoft-office`

* [Chrome Canary](https://www.google.de/chrome/browser/canary.html)
* [FileZilla](https://filezilla-project.org/download.php?type=client)
* [Trello](https://itunes.apple.com/de/app/trello/id1278508951?mt=12) > App Store
* [Pixelmator Classic](https://itunes.apple.com/de/app/pixelmator/id407963104) > App Store

* [MarkEdit for Markdown - Text-Editor](https://apps.apple.com/app/id1669953820)
* [Latest - Software Update Checker](https://max.codes/latest/) `brew install latest`
* [Clipy - Clipboard extension app for macOS](https://github.com/Clipy/Clipy) `brew install clipy`
* [Tiles - The window manager for macOS](https://www.sempliva.com/tiles/) `brew install tiles`
* [Hidden Bar - Hide menu bar icons](https://github.com/dwarvesf/hidden) `brew install hiddenbar`
* [Shottr - Screenshot Tool mit Scrollshot](https://shottr.cc/) `brew install shottr`
* [Google One VPN](https://one.google.com/about/vpn?hl=de)

### Hardware-spezifisch

* [Logitech Options+ App - Tastatur-Einstellungen](https://www.logitech.com/de-de/software/logi-options-plus.html)
* [Logitech Logi Bolt App - Pairing-Einstellungen](https://support.logi.com/hc/de/articles/4418089333655)

### Nice to have

* [Virtual Box](https://www.virtualbox.org/wiki/Downloads) (Nicht mit Apple M1 Chip kompatibel!)
* [NameChanger](https://mrrsoftware.com/namechanger/) `brew install namechanger`
* [Gemini 2 - Der intelligente Duplikatscanner](https://macpaw.com/de/gemini)
* [Miro Video Converter](http://www.mirovideoconverter.com/)
* [LosslessCut - Simple, cross platform video editor](https://github.com/mifi/lossless-cut)
* [Android File Transfer](https://www.android.com/filetransfer/)
* [MemoryClean](https://itunes.apple.com/de/app/memory-clean-monitor-free/id451444120)
* [Pika - Color Picker](https://superhighfives.com/pika) `brew install pika`
* [Free Video Converter](https://itunes.apple.com/de/app/free-video-converter/id464195348?mt=12)
* [Fliqlo - Flip clock screensaver](https://fliqlo.com/screensaver/)
* [SquirrelDisk - Speicherplatzanalyse](https://github.com/adileo/squirreldisk)
* [Bildschirmschoner Flip Clock](https://fliqlo.com/screensaver/)

### Chrome Erweiterungen

* [Save to Pocket](https://chrome.google.com/webstore/detail/save-to-pocket/niloccemoadcdkdjlinkgdfekeahmflj)
* [Deaktivierungs-Add-on von Google Analytics](https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh)
* [Google Übersetzer](https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb)
* [Pesticide for Chrome](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh)
* [Validity](https://chrome.google.com/webstore/detail/validity/bbicmjjbohdfglopkidebfccilipgeif)
* [Full Page Screen Capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
* [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
* Evernote Web Clipper
* AdBlock

### MacOS Quick Look (Datei Vorschau) erweitern

* ~~[All-in-one Quick Look plugin](https://github.com/samuelmeuli/glance)~~

## Developer Setup

### Basics
* Ab macOS Catalina ist [zsh](https://www.zsh.org/) die Standard Shell
* [Oh-My-Zsh](http://ohmyz.sh/)
  * Installation via curl `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
  * Weitere Einstellungen im Abschnitt ganz unten
  * Weitere Details & Infos [Link](https://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
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
* wegmeister Hausschrift installieren

### Git SSH Keys erstellen

* [Anleitung Github](https://help.github.com/articles/generating-ssh-keys/)
* [Anleitung Bitbucket](https://confluence.atlassian.com/bitbucket/set-up-an-ssh-key-728138079.html)

### Websites Ordner erstellen

* Im Benutzer-Profil einen Ordner `Sites` erstellen. Dieser bekommt dann automatisch das Icon.
* Darin eine .htaccess mit folgendem Inhalt erstellen `Options +Indexes`

### SMB Verbindung - Signierung deaktivieren

* [Turn off packet signing for SMB 2 and SMB 3 connections](https://support.apple.com/en-us/HT205926)

## Programm Einstellungen

### FileZilla

* Servermanager Einträge importieren
* Einstellungen > Übertragungen > Maximale Anzahl gleichzeitiger Übertragungen: 6
* Einstellungen > Übertragungen > FTP: Dateitypen > Standard-Übertragungstyp: Binär
* Einstellungen > Bearbeiten von Dateien > Benutzerdefinierten Editor verwednden > `"/Applications/Visual Studio Code.app"`

### Shottr

* General
  * Window Screenshot Background > Solid Color (#404448)
  * Screenshot folder: Desktop
  * Resize retina screenshots: deaktivieren
  * Post screenshot: Show & Copy aktivieren
  * After Area Crop, show: Thumbnail
* Hotkeys
  * Area screenshot: `cmd` + `Shift` + `4`
  * Active window screenshot: `cmd` + `Shift` + `5`
  * Instant Text/OR Recognition: löschen
* Advanced
  * Action when hiding with ESC: Copy Image & Save Image aktivieren

### Clipy

* Zwischenablageverlauf
  * Maximal 50 Einträge
* Tastenkombinationen > Standardeinstellungen übernehmen
* Snippets können aus bestehendem Setup exportiert und neu importiert werden

### TextEdit

* Einstellungen > Neues Dokument
  * Format: Reiner Text
  * Schrift: Hack Regular, 16

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

### Evernote

* Ansichtsoptionen > Notizlistenansicht "Leiste seitlich"
* Ansichtsoptionen > Spalten > Schlagwörter deaktivieren
* Menü Ansicht > "Notizanzahl in Seitenleiste anzeigen" aktivieren

### Logitech Options+

* Tastatur-Einstellungen
  * F4 > Desktop anzeigen/verbergen

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

### iTerm2 + ZSH

* Theme Neu 2021: [Sindre Sorhus' Snazzy color theme.](https://github.com/sindresorhus/iterm2-snazzy)
* Cobalt2 Theme von Wes Bos [Anleitung](https://github.com/wesbos/Cobalt2-iterm)
  * Powerline Schritt übersprungen
  * Patched Hack Font Download siehe oben
* [trash - Dateien & Ordner 'in Papierkorb' löschen](https://github.com/sindresorhus/trash)
* [Set the iTerm tab title to the current directory, not full path](https://gist.github.com/phette23/5270658)
* [iTerm2 - how to pimp yout macOS terminal](https://www.aptgetupdate.de/2017/04/12/howto-iterm2-pimp-your-macos-terminal/)
* [Settings to emojify and prettify your terminal (iTerm2 & ZSH)](https://www.stefanjudis.com/blog/declutter-emojify-and-prettify-your-iterm2-terminal/)


