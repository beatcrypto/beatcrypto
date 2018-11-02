
Debian
====================
This directory contains files used to package beatcryptod/beatcrypto-qt
for Debian-based Linux systems. If you compile beatcryptod/beatcrypto-qt yourself, there are some useful files here.

## beatcrypto: URI support ##


beatcrypto-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install beatcrypto-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your beatcryptoqt binary to `/usr/bin`
and the `../../share/pixmaps/beatcrypto128.png` to `/usr/share/pixmaps`

beatcrypto-qt.protocol (KDE)

