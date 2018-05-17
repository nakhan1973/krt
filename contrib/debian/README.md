
Debian
====================
This directory contains files used to package krtd/krt-qt
for Debian-based Linux systems. If you compile krtd/krt-qt yourself, there are some useful files here.

## krt: URI support ##


krt-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install krt-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your krtqt binary to `/usr/bin`
and the `../../share/pixmaps/krt128.png` to `/usr/share/pixmaps`

krt-qt.protocol (KDE)

