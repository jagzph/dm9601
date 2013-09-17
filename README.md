dm9601
======

DM9601 USB LAN Driver for CentOS 6.x


to build
========

shell$ sudo make 


to install 
==========

shell$ sudo make install

to clean
========

shell$ sudo make clean


NOTE:
=====
This dm9601.c is a modified version of original code from linux kernel branch tree
tailor fit to work on any USB LAN chipset DM9601 (CDR-KING model in the Philippines) 
I do not guarranty any of it to work on your USB LAN device

PROBLEM/LIMITATION
* this works only at USB 1.1 compatibility and speed 
* Placing two USB LAN (CDR-KING) in one server/pc will cause MAC address problem (I have 2 of this with same MAC)
* Speed is terrible slow sometimes disconnect
* Reliability is a big question (not to be used in production)
