
Debian
====================
This directory contains files used to package sucrd/sucr-qt
for Debian-based Linux systems. If you compile sucrd/sucr-qt yourself, there are some useful files here.

## sucr: URI support ##


sucr-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sucr-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sucr-qt binary to `/usr/bin`
and the `../../share/pixmaps/sucr128.png` to `/usr/share/pixmaps`

sucr-qt.protocol (KDE)

