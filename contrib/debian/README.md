
Debian
====================
This directory contains files used to package dashd/fatzchain-qt
for Debian-based Linux systems. If you compile dashd/fatzchain-qt yourself, there are some useful files here.

## fatzchain: URI support ##


fatzchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install fatzchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fatzchain-qt binary to `/usr/bin`
and the `../../share/pixmaps/dash128.png` to `/usr/share/pixmaps`

fatzchain-qt.protocol (KDE)

