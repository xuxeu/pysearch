jobs
查看停止进程列表

jobs -l
显示停止进程的详细列表

然后可以通过如下命令杀死或激活停止的进程

kill %1
%1是将被杀死的job进程号

fg %1
%1是将要被集获得job进程号

fg的全称：foreground，前台，可以唤醒suspended的进程
