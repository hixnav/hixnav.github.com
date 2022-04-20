# 安装

### 获取HixNav

获取windows版本，点击<a href="./hixnav.exe">下载</a>

获取Linux版本，点击<a href="./hixnav">下载</a>

查看源码，请访问仓库<a href="https://github.com/hixnav/hixnav">HixNav</a>

### 配置

>你需要一个Mysql的数据库，以及一个对象存储服务，这些服务可以从云服务厂商那里获取。

###### 配置系统环境变量

```shell
# mysql
# DNS={user}:{password}@tcp({host}:{port})/haixin?charset=utf8mb4&parseTime=True&loc=Local
DNS

# tecentCOS
# COS=https://%s-{your}.myqcloud.com/
COS 
COSSecretID
COSSecretKey
``` 

### 运行

```shell
$ hixnav
```

### 访问

> 系统默认使用80端口

http://{ip}



