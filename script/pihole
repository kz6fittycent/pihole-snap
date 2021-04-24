#!/bin/sh

# Installer script for the Pi-Hole Installer Script
# Attempt to install in a snap environment using SNAP_USER_DATA

set -e
(
	cd $SNAP_USER_DATA
	$SNAP/wget -O basic-install.sh https://install.pi-hole.net
        $SNAP/sudo bash basic-install.sh
)
