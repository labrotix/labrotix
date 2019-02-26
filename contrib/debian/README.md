
Debian
====================
This directory contains files used to package labrotixd/labrotix-qt
for Debian-based Linux systems. If you compile labrotixd/labrotix-qt yourself, there are some useful files here.

## labrotix: URI support ##


labrotix-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install labrotix-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your labrotixqt binary to `/usr/bin`
and the `../../share/pixmaps/labrotix128.png` to `/usr/share/pixmaps`

labrotix-qt.protocol (KDE)

