locate  文件名
在后台数据库中按文件名搜索，搜索速度更快

/var/lib/mlocate
locate命令所搜索的后台数据库

updatedb
更新数据库

数据库一般一天自动更新一次
locate只能按照文件名搜索

搜索规则遵循配置文件：
/etc/updatedb.conf
PRUNE_BIND_MOUNTS ="YES"
#开启搜索限制

PRUNEFS = 
#搜索时不搜索的文件系统

PRUNENAMES = 
#搜索时不搜索的文件类型

PRUNEPATHS = 
#搜索时不搜索的路径
