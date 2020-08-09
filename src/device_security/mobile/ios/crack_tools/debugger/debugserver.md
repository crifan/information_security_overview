# debugserver

* `debugserver`
  * 是什么：一个终端的应用
    * 也是：`XCode`去调试iOS设备中程序时候的进程名
  * 在哪里：iOS设备中
    * 位置：`/Developer/usr/bin/debugserver`
    * 注：iOS中默认没安装
      * iOS中安装`debugserver`
        * 在设备连接过一次`Xcode`，并在`Window`->`Devices`中添加此设备后
          * `debugserver`才会被`Xcode`安装到`iOS`的`/Developer/usr/bin/`下
  * 作用：作为服务端，接受来自远端的`gdb`或`lldb`的调试
    * 可以理解为：`lldb`的`server`
  * 为何需要
    * iOS中，由于App运行检测到越狱后会直接退出，所以需要通过`debugserver`来启动程序
  * 通过`debugserver`来启动程序
    * 举例
      * `debugserver -x backboard 0.0.0.0:1234 ./*`
      * `debugserver *:1234 -a "MoneyPlatListedVersion"`
