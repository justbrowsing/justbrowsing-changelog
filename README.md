0.3-5
================================
2013-04-29

Changelog:
* Fixed adeskbar panel size with autosize script
* Optimized bookmark panel for 1024px wide
* Added a lot of new bookmarks
* Added Firefox extensions: hide my ass, menu icons plus, offline qr generator, turn off the lights
* Added Chrome extensions addthis, chrome to mobile, hide my ass, save to google drive, screen capture
* Firefox 20.0.1 & Google Chrome 28.0.1485.0 dev
* Updated to linux kernel 3.8.10
* Added blog posts
* Revised homepage again

Known bugs:
* Lockscreen wallpaper still cut off
* Max resolution 1024x768 in QEMU
* Setting -vga to vmware results in black screen


0.3-4
=================================
2013-04-11

Changelog:
* Updated to latest packages
* Added More in Content UI addon
* Removed Offline QR generator addon
* Added vmware drivers

Known bugs:
* Max resolution 1024x768 in QEMU
* Setting -vga to vmware results in black screen


0.3-3
=================================
2013-04-07

Changelog:
* Revised homepage again
* Added social networking


0.3-2
=================================
2013-03-31

Changelog:
* Revamped the github homepage
* Wrote a SourceForge scraper to more accurately monitor downloads
* Updated to latest packages

Feature To-do:
* Replace buggy "Offline QR generator" addon with qr-send script


0.3-1
=================================
2013-03-29

Changelog:
* Added "More In Content UI" Firefox addon
* Froze linux kernel to 3.7.10 until 3.8+ screen resolution bug fixed upstream
* Updated to latest packages (wayland pulled in)

Feature To-do:
* Replace buggy "Offline QR generator" addon with qr-send script
* Personas?
* Add bookmarks: jolicloud, rollapp, pixlr, draftin ?
* Test more addons
* Try to get radiotray working


0.3-0
=================================
2013-02-21

Changelog:
* First public release
* Uploaded ISO to SourceForge
* A lot more added to github repos
* Updated to latest


0.2-7
=================================
2013-02-19

Changelog:
* Fixed ethernet bug
* Released source to github

Feature to-do:
* Release more to github
* Upload ISO to sourceforge


0.2-6
=================================
2013-02-17

Changelog:
* Upgrade to kernel 3.7.9
* Set ui.allow_platform_file_picker to false in Firefox
* Added bookmark: http://www.google.com/insidesearch/tipstricks/basics.html
* Added firefox bookmark: chrome://browser/content/places/places.xul
* Added chrome bookmarks: chrome://history, chrome://bookmarks
* Fixed lockscreen
* Fixed Google Drive icon

Known bugs:
* Ethernet doesn't connect by default!


0.2-5
=================================
2013-02-13

Changelog:
* Created new 24px icons
* Created new 16px icons
* Decreased panel from 48px to 24px
* Revamped wageclock layout
* Added features to wageclock
* Fixed buttons in timers
* Added keybindings to calculator
* Removed Aardvark from bookmarks toolbar
* Added [Search] Tips bookmark
* Added Places bookmark
* Added /usr/bin/firefox as file handler
* Added Offline QR generator to Firefox

Known bugs:
* Calculator clear bug with keyboard

Feature To-do:
* Set ui.allow_platform_file_picker to false in Firefox
* Add bookmark: http://www.google.com/insidesearch/tipstricks/basics.html
* Add bookmark: chrome://browser/content/places/places.xul
* Fix drive icon by clicking "learn more"
* Fix patched lockscreen


0.2-4
===============================
2013-01-21

Changelog:
* Added vga=791 to fix glitching caused by quiet
* Re-added VT lockout
* Fixed calculator error message
* Renamed "Most Visited" to "Recent"
* Added playlist.com to bookmarks
* Added www.playlist.com to Chrome whitelist
* Implemented autosize backgrounds script

Known bugs:
* x86_64 drivers not working
* Bootsplash distorted with Nouveau

Feature To-do:
* Create x86_64 /usr/lib/modules squashfs
* Fix webapp icons
* Modify wageclock


0.2-3
===============================
2013-01-20

Changelog:
* Generated x86_64 initrd
* Appended quiet splash to boot menu
* Boot splash now working
* Added 3 second timeout
* Fixed bootsplash logo

Known bugs:
* x86_64 drivers not working
* Distorted boot pre-splash
* Calculator max digits length error incorrect

Feature To-do:
* Create x86_64 /usr/lib/modules squashfs
* Implement new backgrounds
* Add playlist.com to bookmarks
* Fix webapp icons
* Modify wageclock


0.2-2
=============================
2013-01-19

Changelog:
* Updated to latest packages
* Updated live tools to ARCH_201301
* Added x86_64 kernel
* Disabled VT lockout temporarily
* Added bootsplash
* Added dx to bookmarks
* Fixed duckduckgo icon in Firefox
* Added www.youtube.com to Chrome flash whitelist
* Enabled flashblock in Firefox via Toolbar Buttons extension
* Removed quickjava extension
* Created wallpapers and lockscreen for alternate resolutions
* Added package list to livecd

Known bugs:
* Boot menu overlaps logo
* x86_64 kernel does not boot properly

Feature To-do:
* Custom lock dialog
* Implement new backgrounds
* Debug kernel panics
* Fix webapp icons
* Modify wageclock


0.2-1
=========================
2013-01-18

Changelog:
* Fixed wifi key dialog (installed: network-manager-applet-gtk2, gnome-keyring, gcr, libcap-ng)
* Fixed touchpad configuration (/etc/X11/xorg.d/10-synaptics.conf)
* Added gmail video chat plugin
* Increased panel from 32px icons to 48px
* Added i3 "secret" hotkeys
* Fixed i3lock hotkey
* Fixed calculator daisy-chain operations
* Fixed calculator long numbers
* Expanded calculator from 9 to 11 digit display
* Added calculator buttons: plus/minus, square root, exponent, pi constant, e constant
* Added finer grain timer intervals
* Fixed eggtimer logic
* Created stopwatch and egg background images for timers
* Fixed character 1 width in DS-Digital font with fontforge

Known bugs:
* Kernel panic on plug in usb wifi card
* File-handlers default to Firefox
* Wallpaper stretched horizontally
* Lockscreen cut-off vertically
* Filesystem not hidden from user/browser (need to try sandfox again)
* Livecd: Boot messages are displayed
* Livecd: Splash screen not working
* Livecd: Slow bootup as filesystem uncompressed
* Livecd: Syslinux bootscreen is ugly

Feature To-do:
* Custom lock dialog
* Alter wallpaper dimensions
* Debug kernel panics
* Fix webapp icons
* Modify wageclock
* Add www.youtube.com to chrome whitelist
* Fix firefox/chrome bookmark icons
* Add dealextreme to shopping bookmarks


0.2-0
===========================
2013-01-15

Changelog:
* Updated to latest. Firefox 18/Chrome 24
* Added webapps: notes, calculator, timer, email, wageclock
* Added bookmarks to Chrome
* Modded lockscreen: height, mouse and other
* Added wbar to lockscreen
* Cleanup

Known bugs:
* Inherits existing bugs
* Kernel panic on plug in usb wifi card
* Calculator needs substring(0,9) for small numbers
* Calulator needs equals() between operations
* Eggtimer bugs
* File-handlers default to Firefox

Feature To-do:
* Gmail video chat plugin: google-talkplugin
* Touchpad changes: xf86-input-synaptics libsynaptics /etc/X11/xorg.conf.d/10-synaptics.conf
* "Skin" timer "app"
* Custom lock dialog
* Alter wallpaper dimensions
* Debug wireless issues
* Enable i3 WM mode toggle
* Fix webapp icons


0.1-7
============================
2013-01-03

Changelog:
* First actually working livecd
* Fixed chainload issue by deleting fstab
* Fixed firefox close button via Toolbar Buttons extension
* Removed ctrl+f = fullscreen keybinding in i3 config
* Fixed keyboard volume bindings with pulseaudio_ctl

Known bugs:
* Wallpaper stretched horizontally
* Lockscreen cut-off vertically
* Touchpad clickpad enabled
* Touchpad two-finger scrolling enabled (prefer scroll on right)
* Possible Chrome browser forkbomb issue
* Clicking wireless network won't connect (because the WPA key dialog doesn't popup)
* Filesystem not hidden from user/browser (need to try sandfox again)
* Boot messages are displayed in livecd
* Splash screen not working in livecd
* Slow bootup as filesystem uncompressed
* Syslinux bootscreen is ugly

Tested with:
* ATI Radeon Express 200 (radeon driver)
* Intel 945GMS (intel driver)
* Nvidia Geforce 7600 Go (nouveau driver)
* I-ODD livecd (55 seconds from isolinux->firefox)
* CD-R livecd (2 minutes 15 seconds from isolinux->firefox)

Untested:
* USB boot
* webcam
* microphone


0.1-6
=========================
2013-01-02

Changelog:
* First conversion from dev install to livecd
* Configuration of Firefox modified
* Configuration of Chrome modified
* Configuration of i3 tweaked

Known bugs:
* "Working" 0.1-6 is just chainloading to hdd
* Upper-right close button doesn't close firefox, just the tab
* CTRL+F = fullscreen instead of find
* Keyboard vol+/- don't work
* Fallback initramfs doesn't work
* Possible Chrome browser forkbomb issue
* Clicking wireless network won't connect because the WPA key dialog doesn't popup.
* Filesystem not hidden from user/browser (need to try sandfox again)
* Boot messages aren't hidden
* Splash screen not working
* Slow bootup as filesystem uncompressed
* Syslinux bootscreen is ugly


0.1-5
===========================
2013-01-01

Changelog:
* Added i3 lockscreen
* Browser profiles stored in RAM
* Disabled VTs
* Disabled SSH
* Disabled panel preferences

Feature To-do:
* Sandbox browsers (sandfox not working)
* Shutdown in lockscreen (physical power button sends graceful shutdown though)


0.1-4
===========================
2012-12-31

Changelog:
* Added i3 WM
* Added Mozilla Firefox
* Added Google Chrome
* Added adeskbar

Feature To-do:
* Add lockscreen


0.1-0
==========================
2012-12-30

Changelog:
* Tested various light-weight WMs
* Tested various browser addons
* Tested various panel docks
* Tested various lockscreens
