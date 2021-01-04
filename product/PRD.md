## Django

官方提供了 pip, apt/yum, git 三种安装方式，建议使用 pip 安装稳定发行版。

主要安装步骤如下：

1. 创建隔离环境
2. pip install django
3. pip install mysqlclient
4. 安装应用服务器： Apache+mod_wsgi(官方文档推荐)  或 Nginx+uwsgi（社区推荐）
