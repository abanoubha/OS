# OS
my journey to a better operating system (__our os__)

> __our os__ stands on the shoulders of the giants
> — Abanoub Hanna

Our OS = Linux Distribution (like Ubuntu) + DE (Gnome, Cosmic or Pantheon) + Software Tools

## Vison

smart OS that is ours

- smart package manager: abstraction over __apt__, __flatpak__, __snap__ and __appimage__.
- app store : abstraction with ability to pay-as-you-want option + all supported packaging. (or easy to adopt alt packaging)
- IDE : UI designer + Code editor + autocomplete + __Go__/__Rust__/C/CPP.

## Main features and aspects

- seamless editing
- seamless settings
- terminal friendly with keyboard/mouse/touchpad/touch screen
- GUI friendly w/ keyboard/mouse/touchpad/touch screen
- features that makes sense and help get the job done
- at the speed of thought
- settings GUI, config file, seamless settings
- self-repair
- self-configure

## thoughts

- seamless editing : edit the thing at the thing itself
- seamless settings
- terminal ready : you can do everything in terminal
- ui/ux ready : you can do everything in GUI
- ~tiling window manager~ (in a modern way)
- all key shortcuts
- configurable via __conf files__ or __settings app gui__
- blazing fast with less RAM usage (use RUST)
- dynamic linked apps (work smart)
- ~pm : package manager made for this OS~
- can install .deb , flatpak, snap, .appimage , .. and all linux packages. Add apk (android via anbox), and exe (windows via WINE), and app/pkg (apple - maybe)
- ~HiDPI and loDPI screens / displays~ (Ubuntu-based)
- ~pick stability from Debian and Ubuntu + drivers for VMs and HW.~ (Ubuntu-based)
- touch friendly : big roundy icons and buttons
- developer documentation, video tutorials : for devs
- usage documentation, video tutorials : for users
- pay-as-you-can app store
- ready to use libraries for all various things (text to speech, speech to text, OCR, decoders, encoders, .. )
- support for all display languages and keyboard layouts
- support for Go, Rust, C++, C, Java, Kotlin, Swift (SwiftUI), dart (flutter) .. etc (choose a standard one)
- ~file system (fs) with versioning (like btrfs) with speed~
- reactive programming : not-async=bg and not-sync=blocking.
- touchpad gestures : like gnome 40 or mac os
- usage documentation, video tutorials : for 
- file extension hints at the program used to open the file
- send to desktop (shortcut)
- support flatpak & snap & apt with the first app installed of a package manager
- if you use pacman for example, the error will tell you to use apt or snap or flatpak to install the app

## Finally

Obviously, I can't do all of this alone. So I will select software to combine and get __our os__.

- package manager : both [snap](https://snapcraft.io/store) and [flatpak](https://flathub.org/apps)
- terminal : pre-installed distro emulator w/ [fish](https://fishshell.com/) shell
- video player : [mpv](https://flathub.org/apps/details/io.mpv.Mpv) and/or the pre-installed player
- web browser : [firefox](https://flathub.org/apps/details/org.mozilla.firefox)
- virtual machine : [GNOME boxes](https://flathub.org/apps/details/org.gnome.Boxes)
- screencasting : [obs studio](https://flathub.org/apps/details/com.obsproject.Studio)
- GIF screen recorder : [peek](https://flathub.org/apps/details/com.uploadedlobster.peek)
- point of sale software and inventory managemnet : WIP [POS](https://github.com/abanoubha/pos)
- list all devices connected to wifi router : WIP [conn](https://github.com/abanoubha/conn)
- image optimizer / compressor : WIP
- live transcribe : WIP
- video editor : [kdenlive](https://flathub.org/apps/details/org.kde.kdenlive)
- gaming : [steam](https://flathub.org/apps/details/com.valvesoftware.Steam)
- code editor w autocomplete : ~vscode~ , ~elementary code~ , ~vim~ , [~~Builder~~](https://flathub.org/apps/details/org.gnome.Builder) .. (another one needed)
- office suite : [Libre Office](https://flathub.org/apps/details/org.libreoffice.LibreOffice)
  - Writer (word processing)
  - Calc (spreadsheets)
  - Impress (presentations)
  - Draw (vector graphics and flowcharts)
  - Base (databases)
  - Math (formula editing))
- note taking : [markText](https://github.com/marktext/marktext)
- 3D creation suite : [Blender](https://flathub.org/apps/details/org.blender.Blender)
- Vector Graphics Editor : [inkscape](https://flathub.org/apps/details/org.inkscape.Inkscape)
- Christian : Bible (WIP), Agpeya (WIP)
- screenshot
- file manager
- email client : i just use the website on the web browser
- calendar : pre-installed one
- reminder : _
- contacts : _
- image viewer : pre-installed one
- camera : [cheese](https://flathub.org/apps/details/org.gnome.Cheese)
- voice recorder : _
- dictionary : _
- calculator : pre-installed one
- app store : _
- settings n preferences : _
- image editor : [GIMP](https://flathub.org/apps/details/org.gimp.GIMP)
- audio editor : [Audacity](https://flathub.org/apps/details/org.audacityteam.Audacity)
- fonts : _
- activity monitor or system monitor (aka task manager) : htop
- disk utility : GParted and/or Disks
- Bluetooth file exchange : _
- Wifi connect n file sharing : _
- archiver (zip, rar, 7z, ..) : _
- ftp client : [filezilla](https://flathub.org/apps/details/org.filezillaproject.Filezilla)
- torrent client : [transmission](https://flathub.org/apps/details/com.transmissionbt.Transmission)
- desktop remote access / control : [AnyDesk](https://anydesk.com/en) or [teamviewer](https://www.teamviewer.com/en/)
- UI mockups & UX : [figma](https://flathub.org/apps/details/io.github.Figma_Linux.figma_linux)
- cloud storage client : _
- sqlite browser : [sqlite browser](https://snapcraft.io/sqlitebrowser)
- download manager : _
- fan control : _
- clipboard manager : _
- clock n stopwatch n timer : _
- care center : optimize storage, check hardware, .. etc : _
- PWA support : _
- on-screen keyboard (osk) : _
- image optimizer / compressor : _
- live transcribe : _
- firewall : [ufw](https://snapcraft.io/ufw)
- translation tool : [google translate website](https://translate.google.com/)
- ssh
- scp / rsync
- rsnapshot
