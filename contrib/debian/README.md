
Debian
====================
This directory contains files used to package cryptocashbackd/cryptocashback-qt
for Debian-based Linux systems. If you compile cryptocashbackd/cryptocashback-qt yourself, there are some useful files here.

## cryptocashback: URI support ##


cryptocashback-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cryptocashback-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cryptocashbackqt binary to `/usr/bin`
and the `../../share/pixmaps/cryptocashback128.png` to `/usr/share/pixmaps`

cryptocashback-qt.protocol (KDE)

