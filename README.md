# Saist    (Simple Arch Install Script Template)

Saist is a 26 lines code bash script to install Arch Linux base, base-devel, grub, wget. It's made for my install prefrences, but could be very easily edited to suite on any x86 64 bios hardware.

To run saist from a live Arch iso, run:

 wget        && chmod +x saist

md5sum saist
12dc622e85baed0b7242d25964197c37  saist


 ./saist

# --------------------------------------------------------------------

# Pstins (Post Install Script)

Pstins is a small post install script to run inside an Arch base system. It's made for my install prefrences, but could be very easily edited to suite. 

Pstinst installs: xorg-server xorg-xinit xterm xorg-fonts xorg-twm virtualbox-guest-utils virtualbox-guest-modules-arch linux-headers polkit ttf-liberation leafpad xfce4 xfce4-goodies gvfs sudo 

It also sets up some important config files, and the script drops you into an editor to check or further edit those files. To proceed from nano, just close it (Ctrl + x). The files dropped into for editing can be identified in the upper part of nano. 

To run pstins from a base Arch install, run:

 wget         && chmod +x pstins

md5sum pstins
d9b6677fbc26507e74fb14129c7789b7  pstins


 ./pstins

# --------------------------------------------------------------------

# Aist    (Arch Install Script Template)

Aist (Arch Install Script Template) is a longer version of saist that's setup with feedback to let the user know whats up while running, and is in a more traditional scripting style implementing functions.

 wget            && chmod +x aist

md5sum aist
92e85cf77f9bfc6ff877cd39f9ff639d  aist

  

 ./aist


# --------------------------------------------------------------------



I've tested these in a vbox bios setup so far. 

Partitions: sda1 is root, sda2 is swap, sda3 is home. 

The passwords are set as "test" or "first" for root and jeff.

READ the scripts to assure yourself all is ok. If you're unsure, please don't run them.




