# iwlwifi-firmware
Compiled versions of Intel WiFi iwlwifi firmware for use in OPNSense/FreeBSD/Linux systems

OPNSense 25.1.8 removes Intel iwlwifi from its src.git, which means that if you install that version OPNSense (or later) on a miniPC with an Intel WiFi card, you will lose the WiFi interface.

To fix that, download one of these files, then copy to `/boot/firmware`.

To determine which firmware file to use, dump the errors related to iwlwifi to a file or use `dmesg | grep "firmware image"`.

These files were compiled on Ubuntu using Windows Subsystem for Linux.
