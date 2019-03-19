
Debian
====================
This directory contains files used to package hemporad/hempora-qt
for Debian-based Linux systems. If you compile hemporad/hempora-qt yourself, there are some useful files here.

## hempora: URI support ##


hempora-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hempora-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hemporaqt binary to `/usr/bin`
and the `../../share/pixmaps/hempora128.png` to `/usr/share/pixmaps`

hempora-qt.protocol (KDE)

