Openwrt for Freifunk Meshkit
============================

This is a Openwrt Build Script for Usage with Meshkit Imagebuilder for Freifunk. Its based on openwrt trunk, all packages will be built so opkg can postinstall more packages if anybody wants.

Please be careful using this, its trunk, sometimes with crazy problems. Freifunk Leipzig will sometimes build that, this Meshkit with newest trunk openwrt can be used at

http://firmware.leipzig.freifunk.net:8086/meshkit/

If you need an outdated Firmware, but with Openwrt Attitude Adjustment please have a look at

http://meshkit.freifunk.net

--
Freifunk Leipzig


Tipps
=====

für ath9k: freeswitch pakete scheinen noch probleme zu machen, d.h. .config datei ist manuell zu editieren

für x86: manuell datei editieren.. später vor dem Bauen "make menuconfig" und kvm auswählen, sowie startpartition auf /dev/vda... anstelle /dev/sda ändern!
