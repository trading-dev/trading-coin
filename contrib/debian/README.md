
Debian
====================
This directory contains files used to package TDCd/TDC-qt
for Debian-based Linux systems. If you compile TDCd/TDC-qt yourself, there are some useful files here.

## TDC: URI support ##


TDC-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install TDC-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your TDC-qt binary to `/usr/bin`
and the `../../share/pixmaps/TDC128.png` to `/usr/share/pixmaps`

TDC-qt.protocol (KDE)

