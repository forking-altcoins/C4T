
Debian
====================
This directory contains files used to package coin4traded/coin4trade-qt
for Debian-based Linux systems. If you compile coin4traded/coin4trade-qt yourself, there are some useful files here.

## coin4trade: URI support ##


coin4trade-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install coin4trade-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your coin4trade-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

coin4trade-qt.protocol (KDE)

