# increase-disk-size-linux

# for Ubuntu 20
#vgdisplay

#lvextend /dev/mapper/ubuntu-vg -L +200G

#resize2fs /dev/mapper/ubuntu-vg

#df -h

# for centos 6.x

#vgdisplay

#lvextend /dev/mapper/vg-root -L +200G

#resize2fs /dev/mapper/vg-root

#df -h




# for centos 7 

#vgdisplay

#lvextend /dev/centos/root -L +200G

#xfs_growfs /dev/centos/root

#df -h
