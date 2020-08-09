# lldb-server

* 远程调试
  * 分2个端
    * `lldb client`
      * 运行在 local system
        * 比如 Linux，Mac
    * `lldb server`
      * 不同平台
        * `Linux`和`Android`：`lldb-server`
          * 不依赖于`lldb`
            * 因为：已静态链接包含了`LLDB`的核心功能
            * 对比：`lldb`是默认是动态链接`liblldb.so`
        * `Mac`和`iOS`：`debugserver`
      * 运行在 remote system
      * 实现了remote-gdb的功能
    * 两者通讯
      * 用的是：`gdb-remote`协议
        * 一般是在TCP/IP之上运行
  * 细节详见：
    * `docs/lldb-gdb-remote.txt`
  * 资料
    * 主页
      * Remote Debugging — The LLDB Debugger
        * http://lldb.llvm.org/use/remote.html
