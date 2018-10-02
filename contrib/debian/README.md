
Debian
====================
This directory contains files used to package sekod/seko-qt
for Debian-based Linux systems. If you compile sekod/seko-qt yourself, there are some useful files here.

## seko: URI support ##


seko-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install seko-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sekoqt binary to `/usr/bin`
and the `../../share/pixmaps/seko128.png` to `/usr/share/pixmaps`

seko-qt.protocol (KDE)

