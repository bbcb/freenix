# BlackBox Component Builder for Windows, GNU/Linux, OpenBSD, FreeBSD

**Experimental version 1.9 branch. For production cases use version 1.8 from master branch.**

## Installation requirements

For Alt Education 9.1

	apt-get install i586-libgtk+2-devel.32bit

Ubuntu 18.04 LTS Bionic Beaver / Linux Mint 19.X:

	sudo dpkg --add-architecture i386
	sudo apt update
	sudo apt install libgtk2.0-0:i386 gtk2-engines:i386 gtk2-engines-murrine:i386 libcanberra-gtk-module:i386 gnome-themes-extra:i386

Linux Mint 20 has no package 'gnome-themes-extra:i386', it can be safly ignored. There will be warning in console.

Debian 9.X GNOME/Xfce/KDE

	sudo dpkg --add-architecture i386
	sudo apt update
	sudo apt install libgtk2.0-0:i386 gtk2-engines:i386 gtk2-engines-murrine:i386 libcanberra-gtk-module:i386 gtk2-engines-pixbuf:i386 libatk-adaptor:i386 libgail-common:i386 gnome-themes-standard:i386

Ubuntu 16.04 LTS i386:

	sudo apt-get install libgtk2.0-0 gtk2-engines gtk2-engines-murrine libcanberra-gtk-module gnome-icon-theme-full

Ubuntu 16.04 LTS amd64:

	sudo dpkg --add-architecture i386
	sudo apt-get update
	sudo apt-get install libgtk2.0-0:i386 gtk2-engines:i386 gtk2-engines-murrine:i386 libcanberra-gtk-module:i386 gnome-icon-theme-full

Arch-based systems amd64:

	sudo pacman -S multilib/lib32-gtk2

In OpenBSD use 'wxallowed' flag in mount options for the partition to start BlackBox from.

Authors:

* Oberon microsystems AG
* BlackBox Framework Center
* OberonCore
* Alexander V. Shiryaev
* Igor A. Dehtyarenko
* Ivan A. Denisov
* Anton A. Dmitriev
