
Debian
====================
This directory contains files used to package maximusd/maximus-qt
for Debian-based Linux systems. If you compile maximusd/maximus-qt yourself, there are some useful files here.

## maximus: URI support ##


maximus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install maximus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your maximus-qt binary to `/usr/bin`
and the `../../share/pixmaps/maximus128.png` to `/usr/share/pixmaps`

maximus-qt.protocol (KDE)

