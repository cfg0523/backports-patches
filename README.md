backports-patches
=================

Working frag+ack, chan-qos-frag, and fix-negative-channel-1 patches for latest backports-patched in Arch Linux (available in AUR)

I did not personally write these patches (look over at the aircrack-ng wiki), I just modified these to be compliant with the latest AUR package of backports-patched. Use cower/yaourt/whatever to download backports-patched, then use makepkg and enter interactive mode to configure as needed and compile. For the patches themselves, place these in /etc/makepkg.d/backports-patched/patches/ (most likely need to create these).

Tested with kernel version 3.12+
