# jRootfs&Toolchains
本项目基于ubuntu_core(16.04)进行开发，完全支持jLabSDR无线电实验平台，该项目的所有资源均存放在百度云网盘，主要包含jLinux用到的根文件系统以及编译工具。<br>

## 下载镜像文件
 [下载链接](https://pan.baidu.com/s/1xDd23e0vy_9NyTiGJP1yRQ)<br>

 密码：< qv67 >
## 操作说明
1. 解压文件 tar -xf 文件名<br>
2. 拷贝到启动目录

## 资源目录说明   
ubuntu_user_base_rootfs.tar                        原始版本 <br>
ubuntu-2019-6-10-jRootfs.tar <br>
ubuntu-2019-6-11-jRootfs.tar <br>
ubuntu-2019-8-7-jRootfs.tar.gz                     基于jLabSDR定制内容<br>  
ubuntu-2019-11-22-jRootfs.tar.gz                   加入telnet 和 libstdc++.so.6.0.22库<br>


```
ROOT
│
└───根文件系统
|   |    ubuntu_user_base_rootfs.tar
│   │    ubuntu-2019-6-10-jRootfs.tar
|   |    ubuntu-2019-6-11-jRootfs.tar
|   |    ubuntu-2019-8-7-jRootfs.tar.gz
|   |    ubuntu-2019-11-22-jRootfs.tar.gz
|   |
|
└──toolchain───GCC
             │   |   
             |   |
             |   |
             |   |───────WIN32
             |   |          | gcc-linaro-6.5.0-2018.12-i686-mingw32_arm-linux-gnueabihf.tar.xz
             |   |
             |   |   
             |   |
             |   |───────Linux
             |              | gcc-linaro-6.5.0-2018.12-i686_arm-linux-gnueabihf.tar.xz
             |              | gcc-linaro-6.5.0-2018.12-x86_64_arm-linux-gnueabihf.tar.xz
             |              | sysroot-glibc-linaro-2.23-2018.12-arm-linux-gnueabihf.tar.xz 
             |
             │────SDK  
```
如对上述项目有疑问，可发邮件至yhl@onetek.net进行咨询。
