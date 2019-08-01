# Mein OS X Setup
---


## OS X Systemeinstellungen

* Allgemein
  * Rollbalken einblenden: Beim scorllen
  * Fenster beim Beenden einen Programms schließen: deaktivieren
* Schreibtisch & Bildschirmschoner
  * Bildschirmschoner
    * Starten nach 5 Minuten
    * Mit Uhr anzeigen
  * Mögliche Bildschirmschoner
    * Große digitale Uhrzeit → [Padbury Clock](http://padbury.me/clock/) oder
    * [Apple TV Aerial Views Screen Saver](https://github.com/JohnCoates/Aerial)
* Dock
  * Größe: mittel
  * Vergrößerung aktivieren
  * Position: unten
  * Fenster hinter Programmsymbol im Dock ablegen
  * Dock automatisch ein- und ausblenden
  * Zuletzt verwendete Programme im Dock anzeigen: deaktivieren
* Sicherheit
  * Firewall aktivieren
* Spotlight
  * Alles deaktivieren
* Energie sparen
  * Zeiten einstellen
* Tastatur
  * Text
    * Automatische Korrektur: deaktivieren (Rechtschreibkorrektur ausschalten)
    * Wörter automatisch groß schreiben: deaktivieren
    * Punkt mit doppeltem Leerzeichen hinzufügen: deaktivieren
  * Kurzbefehle
    * In Fenstern und Dialogen mit Tabulatortaste der Reihe nach auswählen (Tastatursteuerung): Alle Steuerungen aktivieren (Wechsel zwischen Buttons per Tabulator-Taste)
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
  * Lautstärke in der Menüleiste anzeige: aktivieren
* Bluetooth
  * Bluetooth in der Menüleiste anzeigen: aktivieren
* Freigaben
  * Gerätenamen ändern (Danach System neustarten)
* Datum & Uhrzeit
  * Uhr
    * Datum und Uhrzeit in der Menüleiste anzeigen
    * Datumsoptionen
      * Wochentag anzeigen: aktivieren
      * Datum anzeigen: aktivieren
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
* Pfadleiste anzeigen
* Statusleiste anzeigen

**Befehle im Terminal ausführen**

* Versteckte Dateien anzeigen → `defaults write com.apple.finder AppleShowAllFiles YES`
* Library Ordner anzeigen → `chflags nohidden ~/Library`



## Basics

* Homebrew installieren
  * `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
* Homebrew Cask installieren
  * `brew tap caskroom/cask`
  * [Formulae durchsuchen](https://formulae.brew.sh/cask/)
* PATH anpassen [Link mit Infos](https://sourabhbajaj.com/mac-setup/Homebrew/)
  * `$ echo 'export PATH="/usr/local/bin:$PATH"' >> ~/.bash_profile`
  * Terminal neu Starten
  * `$ brew doctor` Checkup
* Apps mit Homebrew installieren
  * `brew cask install google-chrome firefox evernote dropbox spotify skype the-unarchiver vlc spectacle alfred keepassx authy atom imageoptim filezilla iterm2 sequel-pro mamp canary appcleaner`



## Tools & Programme
* [Chrome](https://www.google.de/chrome/browser/desktop/index.html)
* [Firefox](https://www.mozilla.org/de/firefox/new/)
* [Evernote](https://evernote.com/intl/de/download/?offer=www_menu)
* [Dropbox](https://www.dropbox.com/downloading?src=index)
* [Spotify](https://www.spotify.com/de/download/mac/)
* [Skype](http://www.skype.com/de/download-skype/skype-for-mac/)
* [The Unarchiver](http://unarchiver.c3.cx/unarchiver)
* [VLC](http://www.vlc.de/vlc_download_mac_os_x.php)
* [Spectacle](https://www.spectacleapp.com/)
* [Alfred](https://www.alfredapp.com/)
* [KeePassX](https://www.keepassx.org/downloads/)
* [Authy MacApp](https://authy.com/download/)
* [Clipy - Clipboard extension app for macOS](https://github.com/Clipy/Clipy)
* [AppCleaner](http://www.freemacsoft.net/appcleaner/)


### Treiber
* [Logitech Options Maus-Einstellungen](http://support.logitech.com/de_de/software/options)
* [Suunto Moveslink App](http://www.movescount.com/de/connect/download?type=moveslink&os=mac)


### Nice to have
* [Basecamp 3 Mac App](https://basecamp.com/help/3/guides/apps)
* [Slack](https://slack.com/ssb/download-osx)
* [MediathekView](https://sourceforge.net/projects/zdfmediathk/)
* [TeamViewer](https://www.teamviewer.com/de/download/mac.aspx)
* [NameChanger](https://mrrsoftware.com/namechanger/)
* [Gemini 2 - Der intelligente Duplikatscanner](https://macpaw.com/de/gemini)
* [Miro Video Converter](http://www.mirovideoconverter.com/)
* [LosslessCut - Simple, cross platform video editor](https://github.com/mifi/lossless-cut)
* [Android File Transfer](https://www.android.com/filetransfer/)


### Developer Basics
* [Atom Editor](https://atom.io/)
* [iTerm2 - Terminal Replacement](https://www.iterm2.com/)
* [zsh](https://www.zsh.org/)
  * `$ brew install zsh`
  * Weitere Details & Infos [Link](https://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
  * [Info Link](https://www.howtogeek.com/362409/what-is-zsh-and-why-should-you-use-it-instead-of-bash/)
* [Oh-My-Zsh](http://ohmyz.sh/)
  * Weitere Einstellungen im Abschnitt ganz unten
  * Weitere Details & Infos [Link](https://sourabhbajaj.com/mac-setup/iTerm/zsh.html)
  * Installation via curl `sh -c "$(curl -fsSL https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"`
* [MAMP](https://www.mamp.info/de/downloads/)
* [Chrome Canary](https://www.google.de/chrome/browser/canary.html)
* [Git Tower](http://www.git-tower.com/download)
* [Fork - git client](https://git-fork.com/)
* [Sequel Pro](http://www.sequelpro.com/download)
* [FileZilla](https://filezilla-project.org/download.php?type=client)
* [Virtual Box](https://www.virtualbox.org/wiki/Downloads)
* [ImageOptim](https://imageoptim.com/)
* [Yarn](https://yarnpkg.com/lang/en/) `brew install yarn`
* [NodeJS](https://nodejs.org/en/download/)
* [NVM](https://github.com/nvm-sh/nvm)
  * Installation via curl `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.34.0/install.sh | bash`
  * Install the latest version with `nvm install node`
  * Install the latest LTS version with `nvm install --lts`


### Mac App Store Links
* [Pixelmator](https://itunes.apple.com/de/app/pixelmator/id407963104)
* [Outbank](https://itunes.apple.com/app/apple-store/id1094254051?pt=59026&ct=website&mt=8)
* [Monosnap - Screenshot Tool](https://itunes.apple.com/ru/app/monosnap/id540348655)
* [Trello](https://itunes.apple.com/de/app/trello/id1278508951?mt=12)
* [Pages](https://itunes.apple.com/de/app/pages/id409201541)
* [MemoryClean](https://itunes.apple.com/de/app/memory-clean-monitor-free/id451444120)
* [Sip Color Picker](https://itunes.apple.com/de/app/sip/id507257563)
* [Free Video Converter](https://itunes.apple.com/de/app/free-video-converter/id464195348?mt=12)


### Chrome Erweiterungen
* [Save to Pocket](https://chrome.google.com/webstore/detail/save-to-pocket/niloccemoadcdkdjlinkgdfekeahmflj)
* [Deaktivierungs-Add-on von Google Analytics](https://chrome.google.com/webstore/detail/google-analytics-opt-out/fllaojicojecljbmefodhfapmkghcbnh)
* [Google Übersetzer](https://chrome.google.com/webstore/detail/google-translate/aapbdbdomjkkjkaonfhkkikfgjllcleb)
* [Pesticide for Chrome](https://chrome.google.com/webstore/detail/pesticide-for-chrome/bblbgcheenepgnnajgfpiicnbbdmmooh)
* [Validity](https://chrome.google.com/webstore/detail/validity/bbicmjjbohdfglopkidebfccilipgeif)
* [LastPass](https://chrome.google.com/webstore/detail/lastpass-free-password-ma/hdokiejnpimakedhajhdlcegeplioahd)
* [Full Page Screen Capture](https://chrome.google.com/webstore/detail/full-page-screen-capture/fdpohaocaechififmbbbbbknoalclacl)
* [React Developer Tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi)
* Evernote Web Clipper
* AdBlock



## Weitere Einstellungen

### NPM Installationen

* Gulp
  * `$ yarn global add gulp`
* Browser Sync
  * `$ yarn global add browser-sync`
* MJML
  * `$ yarn global add mjml`
* NPM Check Updates
  * https://www.npmjs.com/package/npm-check-updates
  * `$ yarn global add npm-check-updates`
  * Benutzung: `$ ncu`


### Fonts
  * [Hack | A typeface designed for source code / Patched fonts for Powerline users.](https://github.com/powerline/fonts/tree/master/Hack)
  * wegmeister Hausschrift installieren

### GitHub SSH Keys erstellen
* [Anleitung](https://help.github.com/articles/generating-ssh-keys/)


### MacOS Quick Look (Datei Vorschau) erweitern
* [Quick Look Plugins](https://github.com/sindresorhus/quick-look-plugins)
  * Installation via Homebrew `brew cask install qlcolorcode qlstephen qlmarkdown quicklook-json qlimagesize webpquicklook suspicious-package quicklookase qlvideo`


### Websites Ordner erstellen
* Im Benutzer-Profil einen Ordner `Sites` erstellen. Dieser bekommt dann automatisch das Icon.
* Darin eine .htaccess mit folgendem Inhalt erstellen `Options +Indexes`


### SMB Verbindung - Signierung deaktivieren
* [Turn off packet signing for SMB 2 and SMB 3 connections](https://support.apple.com/en-us/HT205926)


## Programm Einstellungen

#### FileZilla
* Servermanager Einträge importieren
* Einstellungen → Übertragungen → Dateitypen → Standard-Übertragungstyp: Binär
* Einstellungen → Bearbeiten von Dateien → Benutzerdefinierten Editor verwednden → ```"/Applications/Atom.app"```

#### Alfred
* Spotlight Shortcut deaktivieren: Systemeinstellungen → Tastatur → Kurzbefehle → Spotlight → beide Punkte deaktivieren
* Alfred Hotkey `cmd` + `Space`
* Appearance → Options → "Hide hat on Alfred window" + "Hide menu bar icon" aktivieren
* Eingaben für 5 Minuten behalten
  Advanced → History → "Show latest query if within 5 minutes" aktivieren

#### Monosnap
* General → "Launch at login" aktivieren
* General → After upload: Copy direct image link
* General → After upload: "Open in browser" deaktivieren
* General → After upload: "Short links" aktivieren
* Advanced → Filename template: `%Y%m%d_%W`
* Hotkeys → Capture area `cmd` + `Shift` + `6`
* Hotkeys → Open Editor `cmd` + `Shift` + `0`
* FTP Upload auf eigenen Server

#### Spectacle
* Left Half `alt` + `cmd` + `←`
* Right Half `alt` + `cmd` + `→`
* "Launch Spectacle at Login" aktivieren

#### TextEdit
* Einstellungen → Neues Dokument
  * Format: Reiner Text
  * Schrift: Hack Regular, 16

#### Chrome
* Vor Beenden waren aktivieren → Menü Chrome → "Vor Beenden waren" aktivieren
* Pfad für Downloads ändern auf "Desktop"
* Developer-Tools → Settings → Devices → folgende Custom Devies anlegen
  * Laptop FullHD mit 1920x1080
  * Laptop XL mit 1520x800
  * Laptop LG mit 1280x800
  * Laptop MD mit 1024x768

#### Evernote
* Ansichtsoptionen → "Ansicht seitliche Leiste"
* Einstellungen → Allgemein → "Notizanzahl in Seitenleiste anzeigen" aktivieren
* Einstellungen → Allgemein → "Evernote-Helfer startten, wenn ich den Computer starte" aktivieren
* Einstellungen → Formatierung → Notiztext → Helvetica Neue 13

#### iTerm2 + ZSH
* Cobalt2 Theme von Wes Bos [Anleitung](https://github.com/wesbos/Cobalt2-iterm)
  * Powerline Schritt übersprungen
  * Patched Hack Font Download siehe oben
* [trash - Dateien & Ordner 'in Papierkorb' löschen](https://github.com/sindresorhus/trash)
* [Set the iTerm tab title to the current directory, not full path](https://gist.github.com/phette23/5270658)
* [iTerm2 - how to pimp yout macOS terminal](https://www.aptgetupdate.de/2017/04/12/howto-iterm2-pimp-your-macos-terminal/)
