# Surface-Pro-6-Hackintosh-
Latest Surface Pro 6 Hackintosh with Mojave, Catalina, Big Sur and Monterey.

WE ALL KNOW THAT HACKINTOSH ON S SURFACE PRO LAPTOP IS VERY COMPLICATED AND HARD WORKING, BUT AFTER ONE YEAR OF CONSTANT SERACHING AND GOOGLING, I FINALLY MANAGED TO CREATE OPENCORE
EFI FOR SURFACE PRP 6, Well am not sure if this EFI will work for other Surface Pro laptops but you can give it a try.

So now LETS START THE PROCESS!

1] Download and Install diskGenius software from this link https://www.diskgenius.com/ and install.
2] Download the Surface Pro 6 EFI Updated from the attached files or here's the alternate link for my EFI https://drive.google.com/drive/folders/18ysFfC3JkILfKfdKL5HetGFwgmNJwqy9?usp=sharing
3] Now from here you can download your desired macos installer dmg file http://mirrors.dtops.cc/ISO/MacOS/ [ IMPORTANT;~ Only Mojave, Catalina, Big Sur and Monterey is Tested] 
4] After downloading the macos DMG file, download and install this software https://www.balena.io/etcher/
5] Now open balena etcher and select the DMG of macos that u have just downloaded, then plug in your 16gb USB [ Make sure to format USB FIRST] and after plugging in click on Flash.
6] After flashing process completed, open diskgenius and in the EFI partition of your USB and delete the EFI file permanently and now drag and drop the my EFI file in USB EFI partition
7] now just simply restart ur surface pro 6 and boot to UEFI and disable secure boot and unselect all Storage devices except USB Storage, we have to boot the USB, click on restart.
8] now OpenCore will boot and select macOS Installer and (am assuming that u already have made Partition from C drive for your Mac partition) 30gb for cata, 40gb big sur, 50gb Monterey.
9] after macos installer booted click on disk utility and click continue and select the partiton that u have made for macos and format it with macos extended journaled or APFS for big sur and monterey.
10] Aftee formattin, quit disk utiluty and install macos as your would normanlly do. AM SURE ITS ENOUGHT TO UNDERSTAND FOR YOU TO INSTALL MACOS ON YOUR SURFACEN PRO 6.

Heres IMPORTANT PART COMES :}
CATALINA; ALL WORKS EXCEPT WIFI WIRELESS DRIVER AND BLUETOOTH.  [AFCOURSE FIXABLE THROUGH WIFI ADAPTER AND BLUETOOTH ADAPTER]
BIG SUR; SAME FOR WIFI AND BLUETOOTH BUT IN BIG SUR U WILL NOT BE ABLE TO SEE THE TRACKPAD SETTINGS LIKE NO TRACKPAD FOUND BUT KEYBOARD TRACKPAD WILL WORK BUT U WILL NOT BE ABLE TO CUSTOMIZE THE TRACKPAD.
MONTEREY; SAME BUT IN MONTEREY TRACKPAD FULLY GETS NON FUNCTIONAL.

well if want to use ur android phone to use internet on ur hackintosh than here the Horndis package https://drive.google.com/file/d/12APDuCjHhvaaxxjCQduGy_rSreByXOiD/view?usp=sharing
Important; Horndis works normal in mojave and catalina but if u want to use in bigsur or monterey than disabe SIP from recovery and install horndis and U R ALL SET.
I just hope this tutorial works for u and understand all the important things and for dualboot, just place my EFI in ur system EFI partiton and make sure u don't delete the Microsoft folder under EFI, just replace BOOT and OC folder and select internal storage in UEFI and u r good to go.
