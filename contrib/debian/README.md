
Debian
====================
This directory contains files used to package neosd/neos-qt
for Debian-based Linux systems. If you compile neosd/neos-qt yourself, there are some useful files here.

## neos: URI support ##


neos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install neos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your neosqt binary to `/usr/bin`
and the `../../share/pixmaps/neos128.png` to `/usr/share/pixmaps`

neos-qt.protocol (KDE)

