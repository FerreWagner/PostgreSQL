# How To Use PostgreSQL?

一：使用PHP初探pgsql（环境相关配置）

	这里主要对PHP在win下环境做测试



1. win环境下下载pgsql，[LINK](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads "pgsql win下载地址") ，选择pg版本和操作系统下载。next至结尾，会提示安装pgsql工具，可不安装。（此处旨在使用原生sql语句测试）

2.  pgsql默认用户名为：postgres，密码在安装过程中自行设置。

3.  使用PHP连接pgsql前，需要先在php.ini中开启pgsql扩展，搜索并将 **;extension=php_pgsql.dll** 前的分号去掉，重启服务器，使用phpinfo()来查询PHP扩展开启情况，如图所示，则开启。
![开启pgsql扩展](open.png)

4. 使用PHP连接数据库，和大多数主流数据库相同，描述host、port。dbname、userinfo信息即可连接数据库。具体连接方式见 link.php

