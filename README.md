# debianmaker
Scripts to create a debian system from a live environment with debootstrap

This script can debootstrap a Debian Buster system on full ZFS root or
optionally a softraid-lvm-ext4 disk structure.

Using
------
- Boot a live debian on the target machine. (For example: https://grml.org/)
- Download this scripts from github (git clone https://github.com/hyper-prog/debianmaker)
- Enter the debianmaker directory (cd debianmaker)
- Start the "start" script (./start)

The script will ask all the necessary settings on start and runs (as much as possible) unattended way.

