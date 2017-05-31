# saist    (Simple Arch Install Script Template)

Saist25 is a 25 line (a few more now) bash script to install Arch Linux base, base-devel, grub, wget. It's made for my install prefrences, but could be very easily edited to suite on any x86 64 bios hardware.

To run saist25 from a live Arch iso, run:

 wget https://tinyurl.com/saist25 && chmod +x saist25

md5sum saist25

 8a1cab02eb4736fd83035560dfb934d8  saist25

 ./saist25

# --------------------------------------------------------------------

# Pstins (Post Install Script)

Pstins is a small post install script to run inside an Arch base system. It's made for my install prefrences, but could be very easily edited to suite. 

Pstinst installs: xorg-server xorg-xinit xterm xorg-fonts xorg-twm virtualbox-guest-utils virtualbox-guest-modules-arch linux-headers polkit ttf-liberation leafpad xfce4 xfce4-goodies gvfs sudo 

It also sets up some important files, and the script drops you into an editor to check or further edit. To proceed from nano, just close it (Ctrl + x). The file dropped into for editing is printed in the upper part of nano. 

To run pstins from a base Arch install, run:

 wget https://tinyurl.com/pstins && chmod +x pstins

md5sum pstinst

 c4582f24dc313d5aabc73cb8ae4af07c  pstins

 ./pstins

# --------------------------------------------------------------------

I've tested these in only a vbox bios setup so far. 

Partitions: sda1 is root, sda2 is swap, sda3 is home. 

The passwords are set as "first" for root and jeff.

READ the scripts to assure yourself all is ok. If you're unsure, please don't run them.




