# slock - simple screen locker

Build of slock by [Rafael Cavalcanti](https://rafaelc.org/dev).

st is a simple screen locker utility for X.

## Third party patches

- dpms
- mediakeys
- quickcancel
- xresources

## Requirements

In order to build slock you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (slock is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install slock
(if necessary as root):

    make clean install

## Running slock

Simply invoke the 'slock' command. To get out of it, enter your password.
