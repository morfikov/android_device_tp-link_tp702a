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
Display | 1920 x 1080 pixels 5.5"
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
- [ ] Correct screen/recovery size
- [ ] Working Touch, screen
- [ ] Backup to internal/microSD
- [ ] Restore from internal/microSD
- [ ] reboot to system
- [ ] ADB

Medium checks
- [ ] update.zip sideload
- [ ] UI colors (red/blue inversions)
- [ ] Screen goes off and on
- [ ] F2FS/EXT4 Support, exFAT/NTFS where supported
- [ ] all important partitions listed in mount/backup lists
- [ ] backup/restore to/from external (USB-OTG) storage
- [ ] backup/restore to/from adb (https://gerrit.omnirom.org/#/c/15943/)
- [ ] decrypt /data
- [ ] Correct date

Minor checks
- [ ] MTP export
- [ ] reboot to bootloader
- [ ] reboot to recovery
- [ ] poweroff
- [ ] battery level
- [ ] temperature
- [ ] encrypted backups (https://forum.xda-developers.com/showthread.php?t=2011811)
- [ ] input devices via USB (USB-OTG) - keyboard, mouse
- [ ] USB mass storage export
- [ ] set brightness
- [ ] vibrate
- [ ] screenshot
- [ ] partition SD card
