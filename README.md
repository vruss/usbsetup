# A guide for installing and setting up Fedora on a USB

#### this guide applies to any distro. Instructions may variy slightly.

## Requirements
You will need two USBs. One USB you have to make into a live-cd as you normally do when installing a distro. The second USB is the target media and will be where your persistent Fedora installation. 

## Installing
Boot your PC with only your bootable USB plugged in and launch into a live environment. You should see a dialoge window asking you if you want to try or install to hard drive. At this point you plug in your second USB and choose install to hard drive. 

When choosing what drive to install to, choose your USB and make sure you use customized partitioning. 

- Make a 500 MB /boot/efi partition
- Make a 4 000 MB swap partition
- Make a 16 000 MB /home partition
- The rest can go to the root / partition



