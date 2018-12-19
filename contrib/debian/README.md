
Debian
====================
This directory contains files used to package ballastd/ballast-qt
for Debian-based Linux systems. If you compile ballastd/ballast-qt yourself, there are some useful files here.

## ballast: URI support ##


ballast-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ballast-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ballastqt binary to `/usr/bin`
and the `../../share/pixmaps/ballast128.png` to `/usr/share/pixmaps`

ballast-qt.protocol (KDE)

