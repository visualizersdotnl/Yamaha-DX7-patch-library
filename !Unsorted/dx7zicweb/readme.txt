-------------------------------------------------------------------------------------------
Cette collection de banques provenant de Usenet a ete modifies afin de satisfaire les 
besoins des utilisateurs PC.

Les fichiers originaux etaient dans differents formats:

- Certains  n'avaient plus de header sysex (F0 43 ....) ni de checksum 
  (taille 4096 au lieu de 4104)
- D'autres avaient 33 sons dans les banques (le reste a ete vire)
- D'autres encore etaient au format synthworks DX7 pour Atari (4108 bytes)

Actuellement tous font 4104 octets et sont du pure system exclusive:
En tete sysex (F0 43...) + data (4096 octets) + somme de controle et F7. 

Ils peuvent etre envoyes par Cakewalk ou bien par WinSysex sans autre modifications. 
L'extension de fichier est .SYX qui semble etre le standard sur PC.

Ce travail a ete effectue par Jean-Philippe CIVADE (jpcivade@cge-ol.fr) pour le site 
ZiCWeb (http://www.cge-ol.fr/zicweb)

----------------------------------------------------------------------------------------
This collection of patches coming from usenet and have been significantly modified to meet 
PC users requirements. Initially, there wre differents file size and formats. All of Them 
been reduced to one: Pure sysex (extension .SYX)

That means 4104 bytes of data including sysex header (F0 43....) data (4096 bytes) and
trailers (Checksum + F7)

Those bank can be send with cakewalk or winsysex without modification.
This work have been done by Jean-Philippe CIVADE (jpcivade@cge-ol.fr) 
for the musical site ZiCWeb (http://www.cge-ol.fr/zicweb)

----------------------------------------------------------------------------------------
--------------------------------
* This is the original read.me *
--------------------------------

       This is the DX-PEOPLE patch archive, compiled by Glenn Scott.
He can be reached at the address "glenn@otto.lvsun.com."  If that doesn't
work, try "glenn%otto.lvsun.com@decuac.dec.com."

        The archive consists of over 7500 Public Domain synthesizer patches
for the original Yamaha DX7 (as opposed to the DX7II series).  I understand
that the DX7II synths can use original DX7 patches, so these should be fine
for DX7II people.  The archive is stored on a UNIX machine, and I have
transferred all files to convenient MS-DOS disks.

        The files on these 4 disks are, for the most part, bulk dumps
of 32 patches with the headers stripped off.  This means that if you want
to load them into your DX7, you may need to stick a few bytes of system
exclusive information onto the beginning (to say "I am a bulk dump!")
and a checksum and hexadecimal F7 (end-of-exclusive) onto the end.

        Some files have 33 patches in them, and some others do not have the
header stripped off (so they are suitable to send untouched to the DX7).
In addition, some patch librarian software will send the bulk dumps as
they are now.

        The files on this disk named "XXXXXXXX.ALL" (where XXXXXXXX is some
name) contain listings of all patches found in each bulk dump, organized by
author.  In addition, the program that created these files, "names," is
included with its source code.  The program is by me and is also in the
Public Domain.
        To find out about the files on the other 3 disks, see the "README"
or "note" files in each disk and subdirectory.

        Enjoy!  And please give these patches away FREE to your friends.
Spread them around!  It's lots of fun to tell your friends that you want
to give them over 7500 free patches... it really makes their day.

                                                        Dan

#############################################################################
# Dan Barrett   barrett@cs.jhu.edu      (128.220.13.4)  ARPANET             #
#               ins_adjb@jhuvms.bitnet                  BITNET              #
#               ins_adjb@jhunix.UUCP                    UUCP (unreliable)   #
# Dept. of Computer Science, Johns Hopkins University, Baltimore, MD  21218 #
#############################################################################


