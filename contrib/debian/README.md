
Debian
====================
This directory contains files used to package salend/salen-qt
for Debian-based Linux systems. If you compile salend/salen-qt yourself, there are some useful files here.

## salen: URI support ##


salen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install salen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your salen-qt binary to `/usr/bin`
and the `../../share/pixmaps/salen128.png` to `/usr/share/pixmaps`

salen-qt.protocol (KDE)

