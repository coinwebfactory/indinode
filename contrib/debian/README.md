
Debian
====================
This directory contains files used to package indinoded/indinode-qt
for Debian-based Linux systems. If you compile indinoded/indinode-qt yourself, there are some useful files here.

## indinode: URI support ##


indinode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install indinode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your indinodeqt binary to `/usr/bin`
and the `../../share/pixmaps/indinode128.png` to `/usr/share/pixmaps`

indinode-qt.protocol (KDE)

