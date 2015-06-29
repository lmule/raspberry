1. 安装系统

	* 下载最新的树莓派系统-debian
	
        [https://www.raspberrypi.org/downloads/](https://www.raspberrypi.org/downloads/)
	* 下载windows下安装镜像的软件-Win32 Disk Imager
	
        [http://www.onlinedown.net/soft/110173.htm](http://www.onlinedown.net/soft/110173.htm)
	* 安装系统，可以参照如下链接：
	
        [https://github.com/lmule/raspberry/wiki/如何在win系统下安装树莓派的系统到SD卡上](https://github.com/lmule/raspberry/wiki/如何在win系统下安装树莓派的系统到SD卡上)
2. 初始化系统

    * 第一次连接树莓派
        - 使用VGA或者DVI转接口

        	[https://github.com/lmule/raspberry/wiki/使用VGA或者DVI转接口连接树莓派和显示器](https://github.com/lmule/raspberry/wiki/使用VGA或者DVI转接口连接树莓派和显示器)
        - 使用网线连接
        
        	[https://github.com/lmule/raspberry/wiki/使用网线连接树莓派和pc](https://github.com/lmule/raspberry/wiki/使用网线连接树莓派和pc)
    * 连接好树莓派之后，需要对系统进行初始化，第一次进入系统会显示一个蓝色界面（如果需要多次配置，可以运行`sudo raspi-config`）
    ![](http://bbs.ickey.cn/plugins/pubs/kindeditor/attached/image/20140126/20140126092121_41088.jpg)
    
    有几个比较主要的配置，需要修改下：
    	
	* 选择1：扩展硬盘空间；否则的话，硬盘会只有几十M的空间
    	
	* 选择2：修改用户pi的密码
    	
	* 选择4：修改时区和语言选项
	
到这里，树莓派的安装和初始化已经基本完成了。当然里面还有好多其他的配置可以自己调整，更多请见[https://www.raspberrypi.org/documentation/configuration/raspi-config.md](https://www.raspberrypi.org/documentation/configuration/raspi-config.md)
