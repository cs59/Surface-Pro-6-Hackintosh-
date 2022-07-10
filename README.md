# Hackintosh Surface Pro 6
This EFI is specially made for Surface Pro 6, but if u wanna try on other Surface Devices then you can try and can also make some changes.
# Steps to create a bootable macOS USB Installer
Download a dmg file from Olarila - https://www.olarila.com/topic/6278-hackintosh-and-macintosh-olarila-vanilla-images-macos-installer/ OR from http://mirrors.dtops.cc/ISO/MacOS/ 
Note, make sure to make account if u download dmg from olarila.
Now install Balena Etcher - https://www.balena.io/etcher/
Open up balena etcher and plug your formatted USB drive and select dmg file of macOS and select your USB and click START.
After Flashing process completed, download DiskGenius - https://www.diskgenius.com/download.php
Open up Disk Genius and click on ur macos installer usb and click on Boot partition and select files option
then delete the EFI file from ur usb boot partition and place the EFI I provided, make sure to drag and drop EFI folder,
After that you can boot to ur UEFU settings and disable SECURE BOOT and from INTERNAL STORAGE, disable all option except USB Storage and boot
Now you will boot to OPENCORE PICKER and select macos installer and u will be booted to the installer, from that you can install macOS in ur Partition
{Note} if you r installing Catalina, then 30gb storage minimum is needed, if monterey, then maybe 40 or 45gb above
