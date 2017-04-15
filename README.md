# 利用docker-compose技术搭建服务器集群

## 视频例子中用到的配置文件和目录。

* main1.bundle.js : 1号应用服务器使用的主js文件。
* main2.bundle.js : 2号应用服务器使用的主js文件。
* main3.bundle.js : 3号应用服务器使用的主js文件。

* docker-compose.yml : 编排项目的配置文件。
* nginx : 包含负载均衡服务器的配置文件。
* project : 包含构建项目镜像的Dockerfile文件。
* mongo : 数据库的存储目录
