
Debian
====================
This directory contains files used to package sdcd/sdc-qt
for Debian-based Linux systems. If you compile sdcd/sdc-qt yourself, there are some useful files here.

## sdc: URI support ##


sdc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sdc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sdcqt binary to `/usr/bin`
and the `../../share/pixmaps/sdc128.png` to `/usr/share/pixmaps`

sdc-qt.protocol (KDE)

