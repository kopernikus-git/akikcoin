
Debian
====================
This directory contains files used to package akikcoind/akikcoin-qt
for Debian-based Linux systems. If you compile akikcoind/akikcoin-qt yourself, there are some useful files here.

## akikcoin: URI support ##


akikcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install akikcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your akikcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/akikcoin128.png` to `/usr/share/pixmaps`

akikcoin-qt.protocol (KDE)

