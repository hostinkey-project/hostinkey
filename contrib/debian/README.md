
Debian
====================
This directory contains files used to package hostinkeyd/hostinkey-qt
for Debian-based Linux systems. If you compile hostinkeyd/hostinkey-qt yourself, there are some useful files here.

## hostinkey: URI support ##


hostinkey-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install hostinkey-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your hostinkeyqt binary to `/usr/bin`
and the `../../share/pixmaps/hostinkey128.png` to `/usr/share/pixmaps`

hostinkey-qt.protocol (KDE)

