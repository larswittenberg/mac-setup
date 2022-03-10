# Mein OS X Setup

---

## Inspiration

* [macOS Setup Guide](http://sourabhbajaj.com/mac-setup/)
* [macOS Monterey: Setting up a Mac for Development](https://www.taniarascia.com/setting-up-a-brand-new-mac-for-development/)

## OS X Systemeinstellungen

* Allgemein
  * Erscheinugnsbild: Dunkel
  * Rollbalken einblenden: Beim scorllen
  * Fenster beim Beenden einen Programms schließen: deaktivieren
* Schreibtisch & Bildschirmschoner
  * Bildschirmschoner
    * Starten nach 5 Minuten
    * Mit Uhr anzeigen
  * Mögliche Bildschirmschoner
    * Große digitale Uhrzeit [Padbury Clock](http://padbury.me/clock/)
    * [Apple TV Aerial Views Screen Saver](https://github.com/JohnCoates/Aerial)
* Dock & Menüleiste
  * **Screenshot vorhanden**
  * Größe: eher klein
  * Vergrößerung aktivieren
  * Position: unten
  * Fenster hinter Programmsymbol im Dock ablegen: aktivieren
  * Öffnen von Programmen animieren: deaktivieren
  * Dock automatisch ein- und ausblenden: aktivieren
  * Zuletzt verwendete Programme im Dock anzeigen: deaktivieren
  * Anpassungen per Terminal:
    * Animation beim ein/ausblenden deaktivieren: `defaults write com.apple.dock autohide-time-modifier -int 0;killall Dock`
  * Kontrollzentrum
    * AirDrop: In Menüleiste anzeigen: aktivieren
    * Batterie:
      * Im Kontrollzentrum anzeigen: aktivieren
      * In Prozent anzeigen: aktivieren
    * Spotlight: In Menüleiste anzeigen: deaktivieren
    * Uhr
      * Datumsoptionen
        * Wochentag anzeigen: aktivieren
        * Datum anzeigen: aktivieren
* Sicherheit
  * FileVault: aktivieren
  * Firewall: aktivieren
* Spotlight
  * Alles deaktivieren
  * Programme aktivieren
* Energie sparen
  * Zeiten einstellen
* Tastatur
  * Text
    * Automatische Korrektur: deaktivieren (Rechtschreibkorrektur ausschalten)
    * Wörter automatisch groß schreiben: deaktivieren
    * Punkt mit doppeltem Leerzeichen hinzufügen: deaktivieren
  * Kurzbefehle
    * Spotlight
      * Spotlight-Suche anzeigen: deaktivieren
      * Finder-Suchfenster anzeigen: deaktivieren
    * Bewege den Fokus mittels Tastaturnavigation zu Steuerelementen: aktivieren
* Maus
  * Scrollrichtung Natürlich: deaktivieren
* Trackpad
  * Zeigen und Klicken
    * Sekundärklick: Rechts unten klicken
    * Klick durch Tippen: aktivieren
    * Zeigerbewegung: Geschwindigkeit auf ~ 75% stellen
  * Scrollen und Zoomen
    * Scrollrichtung Natürlich: deaktivieren
  * Weitere Gesten
    * Mit streichen Seiten blättern: deaktivieren
* Ton
  * Toneffekte
    * Beim Starten Ton abspielen: deaktivieren
  * Ton in der Menüleiste anzeigen: immer
* Bluetooth
  * Bluetooth in der Menüleiste anzeigen: aktivieren
* Freigaben
  * Gerätenamen ändern
* Displays
  * Auflösung: Skaliert >> Mehr Fläche auswählen
* Bedienungshilfen
  * Zoomen
    * Tastaturkurzbefehle zum Zoomen verwenden: aktivieren
    * Zoomstil: "Bild-in-Bild" (durch die Tastenkombination CTRL + ALT wird eine Lupe eingeblendet)
    * Zoomstil Optionen → Fensterposition: Mauszeiger folgen
  * Anzeige
    * Transparenz reduzieren: aktivieren | [Link](http://osxdaily.com/2016/01/02/disable-transparency-effects-mac-os-x/)

## Finder

* Allgemein
  * Neue Finder-Fenster zeigen: Schreibtisch
* Seitenleiste
  * Objekte zusätzlich aktivieren:
    * Bilder
    * [Benutzername]
    * [Geräte]
    * Festplatten
  * Objekte deaktivieren:
    * CDs, DVDs und iPods
    * Tags
* Erweitert
  * Alle Dateinnamemsuffixe einblenden: aktivieren

Rechtsklick im Finder → Darstellungsoptionen einblenden

* Sortiert nach: Art

Finder Menü-Leiste → Darstellung

* Pfadleiste einblenden
* Statusleiste einblenden

Befehle im Terminal ausführen

* Versteckte Dateien anzeigen → `defaults write com.apple.finder AppleShowAllFiles YES`
* Library Ordner anzeigen → `chflags nohidden ~/Library`

## Basics

* Homebrew installieren
  * `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* Homebrew Cask installieren
  * `brew tap homebrew/cask`
  * [Formulae durchsuchen](https://formulae.brew.sh/cask/)
* PATH anpassen [Link mit Infos](https://sourabhbajaj.com/mac-setup/Homebrew/)
  * `echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile`
  * Terminal neu Starten
  * `brew doctor` Checkup
* Apps mit Homebrew installieren
  * `brew install google-chrome firefox evernote dropbox spotify skype the-unarchiver vlc spectacle alfred keepassx authy imageoptim iterm2 sequel-pro mamp appcleaner tower visual-studio-code github`

## Tools & Programme

* [Chrome](https://www.google.de/chrome/browser/desktop/index.html)
* [Firefox](https://www.mozilla.org/de/firefox/new/)
* [Evernote](https://evernote.com/intl/de/download/?offer=www_menu)
* [Dropbox](https://www.dropbox.com/downloading?src=index)
* [Pocket App](https://itunes.apple.com/us/app/pocket/id568494494?mt=12)
* [Trello](https://itunes.apple.com/de/app/trello/id1278508951?mt=12)
* [Spotify](https://www.spotify.com/de/download/mac/)
* [Skype](http://www.skype.com/de/download-skype/skype-for-mac/)
* [WhatsApp](https://www.whatsapp.com/download/?lang=de)
* [Luminar 3](https://skylum.com/de/luminar)
* [The Unarchiver](http://unarchiver.c3.cx/unarchiver)
* [VLC](http://www.vlc.de/vlc_download_mac_os_x.php)
* [Spectacle](https://www.spectacleapp.com/)
* [Alfred](https://www.alfredapp.com/)
* [KeePassXC](https://github.com/keepassxreboot/keepassxc)
* [Authy MacApp](https://authy.com/download/)
* [AppCleaner](http://www.freemacsoft.net/appcleaner/)
* [Pages](https://itunes.apple.com/de/app/pages/id409201541)
* [Pixelmator](https://itunes.apple.com/de/app/pixelmator/id407963104)
* [Outbank](https://itunes.apple.com/app/apple-store/id1094254051?pt=59026&ct=website&mt=8)
* [Monosnap - Screenshot Tool](https://itunes.apple.com/ru/app/monosnap/id540348655)
* [Clipy - Clipboard extension app for macOS](https://github.com/Clipy/Clipy)
* [Latest - Software Update Checker](https://max.codes/latest/)
* [MarkText - Markdown Editor](https://marktext.app/)

### Hardware-spezifisch

* [Logitech Options Maus-Einstellungen](http://support.logitech.com/de_de/software/options)
* [Suunto Link](https://www.suunto.com/de-de/Support/softwarehilfe/suuntolink/)

### Nice to have~

* ~~[Typora - Markdown Editor](https://typora.io/)~~
* [MediathekView](https://sourceforge.net/projects/zdfmediathk/)
* [TeamViewer](https://www.teamviewer.com/de/download/mac.aspx) `brew cask install teamviewer`
* [NameChanger](https://mrrsoftware.com/namechanger/) `brew cask install namechanger`
* [Gemini 2 - Der intelligente Duplikatscanner](https://macpaw.com/de/gemini)
* [Miro Video Converter](http://www.mirovideoconverter.com/)
* [LosslessCut - Simple, cross platform video editor](https://github.com/mifi/lossless-cut)
* [Android File Transfer](https://www.android.com/filetransfer/)
* [MemoryClean](https://itunes.apple.com/de/app/memory-clean-monitor-free/id451444120)
* [Kelir Color Picker](https://apps.apple.com/de/app/kelir/id1145215534?mt=12)
* [Pika - Color Picker](https://superhighfives.com/pika)
* [Free Video Converter](https://itunes.apple.com/de/app/free-video-converter/id464195348?mt=12)
* [Hidden Bar · Hide menu bar icons](https://github.com/dwarvesf/hidden)
* [Shottr -  Screenshot Tool mit Scrollshot, Color-Picker und Text-Erkennung](https://shottr.cc/)

### Developer Basics

* [Atom Editor](https://atom.io/)
* [iTerm2 - Terminal Replacement](https://www.iterm2.com/) `brew cask install iterm2`
* [zsh](https://www.zsh.org/)
  * `brew install zsh`
  * Weitere Details & Infos [Link](https://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
  * [Info Link](https://www.howtogeek.com/362409/what-is-zsh-and-why-should-you-use-it-instead-of-bash/)
* [Oh-My-Zsh](http://ohmyz.sh/)
  * Weitere Einstellungen im Abschnitt ganz unten
  * Weitere Details & Infos [Link](https://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
  * Installation via curl `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
* [MAMP](https://www.mamp.info/de/downloads/)
* [Chrome Canary](https://www.google.de/chrome/browser/canary.html)
* [Git Tower](http://www.git-tower.com/download) `brew cask install tower`
* [Fork - git client](https://git-fork.com/)
* [Sequel Pro](http://www.sequelpro.com/download) oder [Sequel Ace](https://apps.apple.com/de/app/sequel-ace/id1518036000?mt=12)
* [FileZilla](https://filezilla-project.org/download.php?type=client)
* [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
* [ImageOptim](https://imageoptim.com/)
* [Yarn](https://yarnpkg.com/lang/en/) `brew install yarn`
* [NodeJS](https://nodejs.org/en/download/)
* [NVM](https://github.com/nvm-sh/nvm)
  * Installation via curl `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash`
  * [nvm is broken after I installing oh-my-zsh](https://github.com/robbyrussell/oh-my-zsh/issues/5543)
  * Install the latest version with `nvm install node`
  * Install the latest LTS version with `nvm install --lts`

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

## Weitere Einstellungen

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
  * Benutzung: `ncu`

### Fonts

* [Hack | A typeface designed for source code / Patched fonts for Powerline users.](https://github.com/powerline/fonts/tree/master/Hack)
* wegmeister Hausschrift installieren

### Git SSH Keys erstellen

* [Anleitung Github](https://help.github.com/articles/generating-ssh-keys/)
* [Anleitung Bitbucket](https://confluence.atlassian.com/bitbucket/set-up-an-ssh-key-728138079.html)

### MacOS Quick Look (Datei Vorschau) erweitern

* [All-in-one Quick Look plugin](https://github.com/samuelmeuli/glance)
  * Glance provides Quick Look previews for files that macOS doesn't support out of the box.

### Websites Ordner erstellen

* Im Benutzer-Profil einen Ordner `Sites` erstellen. Dieser bekommt dann automatisch das Icon.
* Darin eine .htaccess mit folgendem Inhalt erstellen `Options +Indexes`

### SMB Verbindung - Signierung deaktivieren

* [Turn off packet signing for SMB 2 and SMB 3 connections](https://support.apple.com/en-us/HT205926)

## Programm Einstellungen

### FileZilla

* Servermanager Einträge importieren
* Einstellungen → Übertragungen → Maximale Anzahl gleichzeitiger Übertragungen: 6
* Einstellungen → Übertragungen → Dateitypen → Standard-Übertragungstyp: Binär
* Einstellungen → Bearbeiten von Dateien → Benutzerdefinierten Editor verwednden → ```"/Applications/Visual Studio Code.app"```

### Alfred

* Alfred Hotkey `cmd` + `Space`
* Appearance → Options → "Hide hat on Alfred window" + "Hide menu bar icon" aktivieren
* Eingaben für 5 Minuten behalten
  Advanced → History → "Show latest query if within 5 minutes" aktivieren

### Monosnap

* General → "Launch at login" aktivieren
* General → After upload: Copy direct image link
* General → After upload: "Open in browser" deaktivieren
* General → After upload: "Short links" aktivieren
* Advanced → Filename template: `%Y%m%d_%W`
* Hotkeys → Capture area `cmd` + `Shift` + `4`

### Spectacle

* "Launch Spectacle at Login" aktivieren
* Alle anderen Einstellungen so belassen

### TextEdit

* Einstellungen → Neues Dokument
  * Format: Reiner Text
  * Schrift: Hack Regular, 16

### Chrome

* Vor Beenden waren aktivieren → Menü Chrome → "Vor Beenden waren" aktivieren
* Pfad für Downloads ändern auf "Desktop"
* Developer-Tools → Settings → Devices → folgende Custom Devies anlegen
  * Laptop FullHD mit 1920x1080
  * Laptop XL mit 1520x800
  * Laptop LG mit 1280x800
  * Laptop MD mit 1024x768

### Evernote

* Ansichtsoptionen → "Ansicht seitliche Leiste"
* Einstellungen → Allgemein → "Notizanzahl in Seitenleiste anzeigen" aktivieren
* Einstellungen → Allgemein → "Evernote-Helfer startten, wenn ich den Computer starte" aktivieren
* Einstellungen → Formatierung → Notiztext → Helvetica Neue 13

### iTerm2 + ZSH

* Theme Neu 2021: [Sindre Sorhus' Snazzy color theme.](https://github.com/sindresorhus/iterm2-snazzy)
* Cobalt2 Theme von Wes Bos [Anleitung](https://github.com/wesbos/Cobalt2-iterm)
  * Powerline Schritt übersprungen
  * Patched Hack Font Download siehe oben
* [trash - Dateien & Ordner 'in Papierkorb' löschen](https://github.com/sindresorhus/trash)
* [Set the iTerm tab title to the current directory, not full path](https://gist.github.com/phette23/5270658)
* [iTerm2 - how to pimp yout macOS terminal](https://www.aptgetupdate.de/2017/04/12/howto-iterm2-pimp-your-macos-terminal/)
* [Settings to emojify and prettify your terminal (iTerm2 & ZSH)](https://www.stefanjudis.com/blog/declutter-emojify-and-prettify-your-iterm2-terminal/)
