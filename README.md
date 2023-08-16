# Android-GRUB
GRUB files to boot Android-x86

## How i use them?
1 : Install your Android-x86 like you normally do, but don't install GRUB.
2 : Boot from a Linux distro liveCD
3 : Download the AndroidGrub.tar.gz file
4 : Extract the 'boot' directory of the archive to your Android partition mount point
5 : Go to your Android partition mount point, and open the grub.cfg file in boot/grub
6 : Change the 'android-2022-03-16' texts to your Android directory (the one on the mount point who contains the initrd and the kernel)
7 : Save all, and reboot to your hard disk

Voila!
