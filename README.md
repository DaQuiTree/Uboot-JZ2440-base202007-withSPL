# Uboot-JZ2440-base202007-withSPL
u-boot patch based on 202007 version and board JZ2440

## 备注
1、制作自己的toolschain（OS: Ubuntu 18.04 材料:crosstool-ng1.24.0  gcc-8.3.0  glibc-2.29  linux-4.20.8  binutils-2.32）

参考：  
[作者: kernel2010 链接](https://blog.csdn.net/kernel2010/article/details/76904080)


2、移植过程

参考:  
[作者: Asymptoteee 链接](https://blog.csdn.net/CallMe_Xu/article/details/107090647)  
[作者: 冉冉云 链接](https://blog.csdn.net/gzxb1995/article/details/103224996)
      
## 未完成

编译结束有报错，提示部分驱动需要使用u-boot的DM模型，但编译出的bin文件可用。

后续需要完成功能：驱动使用设备树与DM模型

