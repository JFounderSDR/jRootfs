# jRootfs
本项目基于u-boot2019进行开发，完全支持jLabSDR无线电实验平台<br>

## 下载镜像文件
 [下载链接](https://eyun.baidu.com/s/3dGJTJQ5)<br>

 密码： jiefang
## 操作说明
1. 解压文件 tar -xf 文件名<br>
2. 拷贝到启动目录



## 资源目录说明  

```
jiefang
│   
│       
│
└───根文件系统
|   |    ubuntu_user_base_rootfs.tar
│   │    ubuntu-2019-6-10-jRootfs.tar
|   |    ubuntu-2019-6-11-jRootfs.tar
|      
│     
│   
│   
│       
└──toolchain───GCC
             │   |   
             |   |
             |   |
             |   |───────WIN32
             |   |          | gcc-linaro-7.4.1-2019.02-i686-mingw32_arm-linux-gnueabihf.tar.xz
             |   |
             |   |   
             |   |
             |   |───────Linux
             |              | gcc-linaro-7.4.1-2019.02-i686_arm-linux-gnueabihf.tar.xz
             |              | gcc-linaro-7.4-2019.02.tar.xz
             |              | sysroot-glibc-linaro-2.25-2019.02-arm-linux-gnueabihf.tar.xz 
             |
             │────SDK  
```
如对上述项目有疑问，可发邮件至yhl@onetek.net进行咨询。