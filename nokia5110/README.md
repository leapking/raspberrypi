#文件说明
PCD8544.c和PCD8544.h是PCD8544控制器的驱动文件
rpi.c是调用NOKIA5110上的PCD8544控制器的程序文件，用于显示操作系统信息。

#详细使用说明
http://blog.lxx1.com/2001

# PCD8544和NOKIA5110介绍
PCD8554是一款低功耗的CMOS LCD控制器，用于驱动48行84列的图形显示，采用串行总线接口与微控制器相连，大大减少了外围控制线的数量，在使用时十分的方便，相对于LCD1602、LCD12864都有着自己的独特优势。
NOKIA 5110是一款基于图形显示的LCD屏，使用的PCD8544控制器。
详细信息：https://www.phodal.com/blog/raspberry-pi-use-nokia-5110-display-ip/

Raspberry Pi有许多的GPIO（General Purpose Input Output：通用输入/输出），可以用来控制和读取数字电路中TTL电平的逻辑0和逻辑1。我们要使用RPi的GPIO首先要知其GPIO的定义，常用的有两种编号定义：WiringPi Pin和BCM GPIO。GPIO的驱动库我这里介绍两种给大家，一种为C语言的WiringPi，另一种为python的RPi.GPIO。
