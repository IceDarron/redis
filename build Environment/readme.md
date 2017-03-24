1.redis下载位置（windows）
===

windows下搭建redis环境，获取redis源码提供如下2种方式:

(1) https://redis.io/download

    官网下载的为未编译源码，需要使用visual studio编译后使用（C++语言编写）,在页面中间有一个windows模块，选择learn more就会跳转到github，如下：
    
    https://github.com/MSOpenTech/redis/releases
   
    该github托管为MS Open Tech组织将redis移植到windows平台的地方。也可以在release中直接下载编译好的压缩包或者msi文件。
    
(2) https://github.com/dmajkic/redis/downloads

    提供一个windows预编译好的redis服务


2.redis下载位置（linux）
===

redis直接支持linux，所以直接在官网下载进行编译即可

http://blog.csdn.net/lixianlin/article/details/7024893

3.redis启动验证
===

http://www.jb51.net/softjc/124506.html

4.关于使用visual studio编译redis源码（熟悉该ide的可以跳过）
===

对于未使用过visual studio（vs）的同学可以参考下，如何使用vs编译redis源码。

vs官网下载：https://www.visualstudio.com/zh-hans/downloads/
vs安装教程：http://jingyan.baidu.com/article/a3761b2bc35c771576f9aaf4.html
通过vs编译redis：http://www.cnblogs.com/raker/p/4368741.html（编译过程可以选择release）

常见问题

redis-server.exe闪退：通过查看日志，发现可能是虚拟内存没有配置
