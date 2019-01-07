
Debian
====================
This directory contains files used to package prontod/pronto-qt
for Debian-based Linux systems. If you compile prontod/pronto-qt yourself, there are some useful files here.

## pronto: URI support ##


pronto-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pronto-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pronto-qt binary to `/usr/bin`
and the `../../share/pixmaps/pronto128.png` to `/usr/share/pixmaps`

pronto-qt.protocol (KDE)

