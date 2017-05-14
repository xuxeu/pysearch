alias
查看别名


alias la='ls -alh --color=auto'
设定命令别名
但这样设置别名，重启系统就会失效。

如果想要别名永久生效，需要写入环境变量配置文件中
vim ~/.bashrc,在该文件中写上别名设置

然后source ~/.bashrc让该文件作的更改立即生效，否则重启才能生效。
