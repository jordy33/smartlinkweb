WebSmartlink
=========

Web Python interface Bluetooth LE 

Release Notes
-------------

Release 0.1.1

Running on Archlinux: Please install the following requirements    

passwd

hostnamectl set-hostname raspberry

timedatectl set-timezone America/Mexico_City

pacman -Syu

Replace lzo2 with core/lzo? [Y/n] n

lzo and lzo2 are in conflict. Remove lzo2? [y/N] y

reboot

pacman -S python

pacman -S python-setuptools

pacman -S python-pip

pacman -S git

pacman -S vim-python3

pacman -S python-pylint

pacman -S sqlite 3

pacman -S bluez

pacman -S bluez-utils

pip install cherrypy

pip install pexpect

Copy the file smarlinkweb.service to /etc/systemd/system
chmod +x smartlinkweb.py
