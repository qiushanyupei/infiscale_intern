Linux系统中，硬盘设备文件通常位于/dev目录下，命名规则如下：<br>
sda：表示第一个硬盘。<br>
sdb：表示第二个硬盘。<br>
sdc：表示第三个硬盘。<br>
以此类推。<br>
每个硬盘可以进一步划分为多个分区，分区的命名规则如下：<br>
sda1：表示第一个硬盘的第一个分区。<br>
sda2：表示第一个硬盘的第二个分区。<br>
sda3：表示第一个硬盘的第三个分区。<br>
一般会分系统启动盘和数据存储盘<br>
<br>
SATA（Serial ATA）(ATA:Advanced Technology Attachment)<br>
分区是对硬件磁盘空间的物理划分，目录是对文件存储结构的逻辑组织<br>
/dev对于挂载非常关键,常常作为挂载源，与物理设备的接口相对应<br>
挂载有几种分类：<br>
1、本地磁盘分区（例：/dev/sda1）<br>
2、U盘/移动硬盘(例：/dev/sdb1)<br>
3、ISO镜像（例：/home/user/file.iso）<br>
4、网络路径(例：192.168.1.10：/share)<br>
5、临时文件系统(属于内存挂载)（例：tmpfs,proc,sysfs）<br>

user的~路径就是root的user路径<br>
