
# Appium 作业 1 

根据课堂视频，安装搭建Appium运行环境，并运行示例代码

<br><br>
## 安装Appium Python Client 包
新版本的Selenium 和Appium Server配合有问题，需要安装最新3.7.0 版本的selenium

怎么看selenium版本
```python
d:\data>python
>>> import selenium
>>> selenium.__version__
'3.7.0'

如果版本不是 3.7.0 

pip uninstall selenium
pip install selenium==3.7.0
```

安装Appium Python Client 包的命令

pip install Appium-Python-Client


<br><br>
## 安装 Appium Server 

下载安装Appium Desktop的安装包，
下载地址 https://github.com/appium/appium-desktop/releases/latest
下载扩展名为.exe的包


<br><br>
## 安装 Android Studio

官方中文网站
https://developer.android.google.cn/studio/archive.html
选择2.3.3 版本，包含了sdk的安装包 Windows IDE bundle with SDK (64-bit)

特别注意，安装程序要求路径中最好不要有空格。


<br><br>
## 安装JDK
百度搜索一下jdk(操作一下)，下载安装就可以

http://rj.baidu.com/soft/detail/14459.html?ald

<br><br>
## 安装安卓模拟器

先试试android studio里面自带的模拟器

打开 studio，创建一个项目，通过tools - android - AVD Manager菜单创建一个安卓模拟设备

-----------


如果不行，可以试试Genymotion，安装过程参考 https://github.com/jcyrss/songqin-testdev/issues/3

<br><br>
## 运行自动化测试
- 运行虚拟机，下载开发者头条应用，http://toutiao.io/s/apk <br>
安装到虚拟机中并运行；<br>
注册一个账号<br>
- 根据课堂教学视频，运行Appium Server，并设置、启动服务<br>
- 下载自动化脚本https://github.com/jcyrss/songqin-testdev/blob/master/appium/src/lesson1/toutiao_login.py
修改其中用户名，密码为你注册的账号，运行脚本完成一个自动登录功能




 

