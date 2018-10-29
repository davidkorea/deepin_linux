# deepin_linux

# Issue 3 - Install Anaconda

0. Go to anaconda website to download linux version

1. ```cd Downloads```

2. ```bash Anaconda3-5.3.0-Linux-x86_64.sh ```

3. continue ```ENTER``` to read 《Anaconda End User License Agreement》

4. ```Do you accept the license terms? [yes|no]```

    ```>>> yes```
    
5. ```Do you wish the installer to initialize Anaconda3 in your /home/xerox/.bashrc ? [yes|no]```

    ```>>> YES```

6. ```For this change to become active, you have to open a new terminal.```

    open a new ternimal run ```conda list```

7. ```jupyter notebook```

# Issue 2 - Disk Read Only

![](https://i.loli.net/2018/10/26/5bd2ed3ee8c66.png)

# Issue 1 - Install 한글

1. ```sudo apt-get install fcitx-hangul```

```
xerox@xerox-PC:~$ sudo apt-get install fcitx-hangul

我们信任您已经从系统管理员那里了解了日常注意事项。
总结起来无外乎这三点：

    #1) 尊重别人的隐私。
    #2) 输入前要先考虑(后果和风险)。
    #3) 权力越大，责任越大。

[sudo] xerox 的密码：
正在读取软件包列表... 完成
正在分析软件包的依赖关系树       
正在读取状态信息... 完成       
将会同时安装下列软件：
  libhangul-data libhangul1
下列【新】软件包将被安装：
  fcitx-hangul libhangul-data libhangul1
升级了 0 个软件包，新安装了 3 个软件包，要卸载 0 个软件包，有 79 个软件包未被升级。
需要下载 1,944 kB 的归档。
解压缩后会消耗 6,861 kB 的额外空间。
您希望继续执行吗？ [Y/n] y
获取:1 http://packages.deepin.com/deepin panda/main amd64 libhangul-data all 0.1.0+git20170815-2 [1,866 kB]
获取:2 http://packages.deepin.com/deepin panda/main amd64 libhangul1 amd64 0.1.0+git20170815-2 [55.1 kB]
获取:3 http://packages.deepin.com/deepin panda/main amd64 fcitx-hangul amd64 0.3.1-1 [23.3 kB]
已下载 1,944 kB，耗时 8秒 (243 kB/s)                                       
正在选中未选择的软件包 libhangul-data。
(正在读取数据库 ... 系统当前共安装有 180597 个文件和目录。)
正准备解包 .../libhangul-data_0.1.0+git20170815-2_all.deb  ...
正在解包 libhangul-data (0.1.0+git20170815-2) ...
正在选中未选择的软件包 libhangul1:amd64。
正准备解包 .../libhangul1_0.1.0+git20170815-2_amd64.deb  ...
正在解包 libhangul1:amd64 (0.1.0+git20170815-2) ...
正在选中未选择的软件包 fcitx-hangul:amd64。
正准备解包 .../fcitx-hangul_0.3.1-1_amd64.deb  ...
正在解包 fcitx-hangul:amd64 (0.3.1-1) ...
正在设置 libhangul-data (0.1.0+git20170815-2) ...
正在处理用于 libc-bin (2.27-3) 的触发器 ...
正在处理用于 hicolor-icon-theme (0.17-2) 的触发器 ...
正在设置 libhangul1:amd64 (0.1.0+git20170815-2) ...
正在设置 fcitx-hangul:amd64 (0.3.1-1) ...
正在处理用于 libc-bin (2.27-3) 的触发器 ...
xerox@xerox-PC:~$ 

```
2. Search hangul and config

![](https://i.loli.net/2018/10/26/5bd2ec2ab3d19.png)
