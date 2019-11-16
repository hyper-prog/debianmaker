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

Features
--------
- The script creates a debian buster system on the target machine.
- It can install a full ZFS filesystem or SoftwareRAID-Lvm-Ext4
- The ZFS datasets / Lvm volumes created according a simple table from a config file.
- The target system can boot via BIOS or UEFI.
- The script works unattended way. The necessary questions are asked only at the start.
- The docker can automatically installed.
- You can configure the scripts to work without any question. (In case you pre-edit the conf file)
