
Debian
====================
This directory contains files used to package sbpayd/sbpay-qt
for Debian-based Linux systems. If you compile sbpayd/sbpay-qt yourself, there are some useful files here.

## sbpay: URI support ##


sbpay-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sbpay-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sbpay-qt binary to `/usr/bin`
and the `../../share/pixmaps/sbpay128.png` to `/usr/share/pixmaps`

sbpay-qt.protocol (KDE)

