# Linux-硬盘挂载
step1: open root
$: https://zhidao.baidu.com/question/1642662411261532620.html
step2: Hard disk mount
$: website: https://oldtang.com/389.html

1. fdisk /dev/sda
2.  g 3. F 4. n 5. F 6.v 7. w 8.df -h 9.sudo fdisk -l (Filesystem UUID: 516dfe9e-0f77-43b3-9c5c-86043870fd01) 10.sudo mount /dev/sda1 /home 11.df -h 12.vi /etc/fstab
