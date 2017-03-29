TeamWin Recovery Project

Device configuration for TP-LINK Neffos C5 MAX (TP702A)
=====================================

Basic   | Spec Sheet
-------:|:-------------------------
CHIPSET | MediaTek MT6753
CPU     | 1.3 GHz Octa-core ARM Cortex A53 CPU
GPU     | ARM Mali-T720 MP3
Memory  | 2 GB
Shipped Android Version | Android 5.1 (Lollipop)
Storage | 16 GB
MicroSD | Up to 32 GB
Battery | 3045 mAh
Dimensions | 152 x 76 x 8.95 mm
Display | 1920 x 1080 pixels 5.5" (403.4 PPI )
Rear Camera  | 13.0 MP
Front Camera | 5.0 MP
Release Date | January 2016

![TP-LINK Neffos C5 MAX](http://www.neffos.com/res/upfile/product/20160107020857.png "TP-LINK Neffos C5 MAX")

How to compile the image
=====================================
You can get the minimal OMNI source [from here](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni).
The full HowTo can be found [here](https://forum.xda-developers.com/showthread.php?t=1943625).

TWRP Functional Checklist
=====================================

Blocking checks
- [x] Correct screen/recovery size
- [x] Working Touch, screen
- [x] Backup to internal/microSD
- [x] Restore from internal/microSD
- [x] reboot to system
- [x] ADB

Medium checks
- [x] update.zip sideload
- [x] UI colors (red/blue inversions)
- [x] Screen goes off and on
- [x] F2FS/EXT4 Support, exFAT/NTFS where supported
- [x] all important partitions listed in mount/backup lists
- [x] backup/restore to/from external (USB-OTG) storage
- [ ] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [x] decrypt /data
- [x] Correct date

Minor checks
- [x] MTP export
- [x] reboot to bootloader
- [x] reboot to recovery
- [x] poweroff
- [x] battery level
- [x] temperature
- [x] encrypted backups
- [x] input devices via USB (USB-OTG) - keyboard, mouse and disks
- [x] USB mass storage export
- [x] set brightness
- [x] vibrate
- [x] screenshot
- [x] partition SD card
