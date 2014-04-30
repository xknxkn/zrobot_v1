zrobot
======

**第一版Zrobot小车工程**  
* hw文件夹中为小车Vivado工程，使用Vivado 2013.4构建  
* sw文件夹中为小车linux 软件工程，app为用户空间程序， driver中包括了一个pwm驱动  
* libs文件夹为一些lib文件， 其中xil_io.h文件为linux用户空间直接对底层硬件寄存器进行读写的两个接口  
本项目推荐使用windows+ubuntu虚拟机的方式来开发  
本项目的硬件工程在window7 64位系统中测试通过， 软件工程在ubuntu 2012.04虚拟机中测试  
# Getting Started
使用如下命令将工程下载到你的本地环境中  
  
  ```
  $git clone https://github.com/xupsh/zrobot_v1.git
  ```

## build hw
