$ cd st
$ vim config.mk

add to the file:

>export CC=gcc
edit PREFIX = /usr/local, change to PREFIX = /usr/

$ sudo pacman -S gcc
$ sudo make clean install
