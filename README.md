# slock - simple screen locker

Build of slock by [Rafael Cavalcanti](https://rafaelc.org/dev), 2021-2023. slock is a simple screen locker utility for X.

_Notice: To cleanly integrate updates from upstream, this branch might be rebased._

## Third party patches

- dpms
- mediakeys
- quickcancel
- xresources

## My own patches

- Complement to mediakeys patch: allow more keys.

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
