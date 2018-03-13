# mikes-crouton
things I run on my chromebook (a Toshiba Chromebook 2 2015)

Helpful Links:
https://github.com/dnschneid/crouton
https://github.com/dnschneid/crouton/wiki/
https://github.com/dnschneid/crouton/wiki/Crouton-Command-Cheat-Sheet

Starting Out in Chrome:

<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>T</kbd>
Create a chroot

`sudo sh ~/Downloads/crouton -t x11,gtk-extra,gnome,gnome-desktop,xorg,xiwi,keyboard`

Start the chroot

`sudo startgnome`



Starting Out in Ubuntu:

`sudo apt-get install python3`

`sudo apt-get install pip3`

Installing a .deb (like vscode or atom): `sudo dpkg -i PACKAGE_NAME`
