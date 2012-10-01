# Mentohust(Android 分支)

创建这个分支是为了让mentohust能在Android上编译通过。

请访问 [Mentohust](http://code.google.com/p/mentohust/) 源项目的地址以获取更多信息。

## License

* [GNU GPL v3](http://www.gnu.org/licenses/gpl.html)

## 使用方法

您可以直接从[这里](http://code.google.com/p/mentohust/)直接下载mentohust，然后通过adb放到手机中：

    adb push [您自己机器上mentohust的地址] /system/bin/mentohust

然后启动它：

    adb shell
    # mentohust

更建议的方法是到[这里](http://code.google.com/p/mentohust/)下载安装包，然后放到手机后安装打开。

## 从源代码构建

## TODO List

  - 将libpcap的依赖去掉，变成Android内置的方式，从而无需root也可运行