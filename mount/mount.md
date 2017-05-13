mount
查询系统中已经挂载的设备

mount -a
依据配置文件/etc/fstab的内容，自动挂载

挂载命令格式
mount [-t 文件系统] [-o特殊选项] 设备文件名 挂载点

选项：
-t 文件系统
加入文件系统类型来指定挂载的类型，可以ext3，ext4，iso9660等文件系统

-o 特殊选项
可以指定挂载的额外选项


挂载光盘
mkdir  /mnt/cdrom/
建立挂载点

mount -t iso9660 /dev/cdrom /mnt/cdrom
mount  /dev/sr0 /mnt/cdrom
挂载光盘






