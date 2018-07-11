
Debian
====================
This directory contains files used to package bmtpd/bmtp-qt
for Debian-based Linux systems. If you compile bmtpd/bmtp-qt yourself, there are some useful files here.

## bmtp: URI support ##


bmtp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bmtp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bmtpqt binary to `/usr/bin`
and the `../../share/pixmaps/bmtp128.png` to `/usr/share/pixmaps`

bmtp-qt.protocol (KDE)

