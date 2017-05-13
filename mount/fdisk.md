fdisk -l

查看系统中已经存在的硬盘

找到对应u盘的设备名，比如sdb1，然后知道u盘文件系统格式，比如vfat

就可以用mount命令来挂载啦！
mount -t vfat /dev/sdb1 /mnt/usb/


注意：
linux默认貌似是不支持NTFS文件系统。
可以通过安装ntfs-3g来支持文件系统，但貌似也不能写入，只可读。
