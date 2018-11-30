
Debian
====================
This directory contains files used to package localtraded/localtrade-qt
for Debian-based Linux systems. If you compile localtraded/localtrade-qt yourself, there are some useful files here.

## localtrade: URI support ##


localtrade-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install localtrade-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your localtradeqt binary to `/usr/bin`
and the `../../share/pixmaps/localtrade128.png` to `/usr/share/pixmaps`

localtrade-qt.protocol (KDE)

