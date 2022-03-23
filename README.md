![logo](https://haixin-1300602599.cos.ap-guangzhou.myqcloud.com/logo.png)

You can use it as a convenient tool, or you can deploy it to the cloud and access your services anytime, anywhere, so start trying

# Try It
### Get HixNav

下载windows版本，点击<a href="./hixnav.exe">下载</a>，下载Linux版本，点击<a href="./hixnav">下载</a>
需要源码<a href="https://github.com/hixnav/hixnav">点击</a>

### Simple configurations

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

### Try to run

```shell
$ hixnav
```
