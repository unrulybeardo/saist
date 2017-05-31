# saist    Simple Arch Install Script Template

Saist25 is a 25 line (a few more now) bash script to install Arch Linux base, base-devel, grub, wget. It's made for my install prefrences, but could be very easily edited to suite on any x86 64 bios hardware.

To run it from the live Arch iso, run:

 wget https://tinyurl.com/saist25 && chmod +x saist25

 md5sum saist25 
8a1cab02eb4736fd83035560dfb934d8  saist25

 ./saist25

#----------------------------------------------------------------------

Pstins is a small post install script to run inside your new saist25 system. Again, very easy to read and edit to suite. 

Pstinst installs: xorg-server xorg-xinit xterm xorg-fonts xorg-twm virtualbox-guest-utils virtualbox-guest-modules-arch linux-headers polkit ttf-liberation leafpad xfce4 xfce4-goodies gvfs sudo 

It also sets up some important files, and drops you into an editor to check or further edit them. To procede from nano, just close nano (Ctrl + x). The file dropped into for editing is printed in the upper part of nano. 

To run pstins from a base Arch install, run:

 wget https://tinyurl.com/pstins && chmod +x pstins

 md5sum pstinst
abb03940150e9d5a8355fa36b95e441c  pstins

 ./pstins

#----------------------------------------------------------------------

I've tested these in only a vbox bios setup so far. 

Partitions: sda1 is root, sda2 is swap, sda3 is home. 

The passwords are set as "first" for root and jeff.

READ the script to assure yourself everything is ok. If you're unsure, please don't run them.




