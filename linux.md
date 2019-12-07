# resize a LVM disk
```
vgs
pvresize /dev/sda1
lsblk
pvresize /dev/sda1
vgs
lvextend -L 13G  /dev/mapper/docker--ubuntu--vg-root
resize2fs /dev/mapper/docker--ubuntu--vg-root
```
