# AlcanSever
智能水族项目：PHP+Mysql+nginx


服务器环境：
1.centos7.0+  
2.MySQL5.6  
3.php5.4.16 
4.nginx1.10.2

一、安装上述服务器软件
二、数据库脚本szx.sql 导入到数据库中，并修改 cardapi/config.php 及 application/database.php 两个文件中的数据库配置
三、压缩文件中的代码上传到服务器，解压到需要部署的目录
四、nginx配置文件中配置运行目录及预埋，接口代码运行根目录为 public 文件夹
五、socket硬件接口文件 为 cardapi/cardapi.php 在命令行中运行此文件： php cardapi/cardapi.php start -d

