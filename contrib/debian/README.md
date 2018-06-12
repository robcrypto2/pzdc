
Debian
====================
This directory contains files used to package pzdcd/pzdc-qt
for Debian-based Linux systems. If you compile pzdcd/pzdc-qt yourself, there are some useful files here.

## pzdc: URI support ##


pzdc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pzdc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pzdcqt binary to `/usr/bin`
and the `../../share/pixmaps/pzdc128.png` to `/usr/share/pixmaps`

pzdc-qt.protocol (KDE)

