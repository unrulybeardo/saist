Nov, 2018 Update:

# inst

The latest Arch install script inst, installs an xfce DE. As with the other older scripts here, this is a template needing edited before use. 
I'd like to think it as some what of a balance between minimal and practical, with the intent of easing things for me, the user. Tested in vbox. 
Admittedly, I need to step things up with updating/replacing my preferred msdos partition table. As far as I know, there's not been new hardware 
available that's compatible with this for quite some time.

To run inst from a live Arch iso, run:

 wget https://raw.githubusercontent.com/Cody-Learner/saist/master/inst && chmod +x inst

or tinyurl: https://tinyurl.com/archinst && chmod +x inst

$ md5sum inst
355ee5d54583c32523a3567b0bec4d21  inst

 ./inst


# --------------------------------------------------------------------

# Saist    (Simple Arch Install Script Template)

Saist is a 26 lines code bash script to install Arch Linux base, base-devel, grub, wget. Easily edited for any x86 64 bios hardware.

To run saist from a live Arch iso, run:

 wget https://raw.githubusercontent.com/jeffscode/saist/master/saist && chmod +x saist
 
or tinyurl: wget https://tinyurl.com/archsaist && chmod +x saist

$ md5sum saist
12dc622e85baed0b7242d25964197c37  saist


 ./saist

# --------------------------------------------------------------------

# Pstins (Post Install Script)

Pstins is a small post install script to run inside an Arch base system. It's made for my install prefrences, but could be very easily edited to suite. 

Pstinst installs: xorg-server xorg-xinit xterm xorg-fonts xorg-twm virtualbox-guest-utils virtualbox-guest-modules-arch linux-headers polkit ttf-liberation leafpad xfce4 xfce4-goodies gvfs sudo 

It also sets up some important config files, and the script drops you into an editor to check or further edit those files. To proceed from nano, just close it (Ctrl + x). The files dropped into for editing can be identified in the upper part of nano. 

To run pstins from an Arch base install, run:

 wget https://raw.githubusercontent.com/jeffscode/saist/master/pstins && chmod +x pstins
 
 or tinyurl: wget https://tinyurl.com/archpstins && chmod +x pstins

md5sum pstins
d9b6677fbc26507e74fb14129c7789b7  pstins


 ./pstins

# --------------------------------------------------------------------

# Aist    (Arch Install Script Template)

Aist (Arch Install Script Template) is a longer version of saist that's setup with feedback to let the user know whats up while running, and is in a more traditional scripting style implementing functions.

To run saist from a live Arch iso, run:

 wget https://raw.githubusercontent.com/jeffscode/saist/master/aist && chmod +x aist
 
 or tinyurl: wget https://tinyurl.com/aist-4-arch && chmod +x aist

$ md5sum aist
66d5e4ff37980d381d7069f375ecaa1a  aist

 ./aist


# --------------------------------------------------------------------



I've tested these in a vbox bios setup so far. 

Partitions: sda1 is root, sda2 is swap, sda3 is home. 

The passwords are set as "test" for root and jeff.

READ the scripts to assure yourself all is ok. If you're unsure, please don't run them.




