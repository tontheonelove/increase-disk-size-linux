# increase-disk-size-vg-root

#vgdisplay

#lvextend /dev/mapper/vg-root -L +200G

#resize2fs /dev/mapper/vg-root

#df -h
