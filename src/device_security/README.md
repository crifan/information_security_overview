# 设备端安全

和Web网络相对应的，可以统称为 设备端的安全。

主要包括：

* PC端
  * Windows
  * Mac
  * Linux
* 移动端
  * Android
  * iOS
* IoT=物联网设备

下面根据不同维度详细介绍。

## 可执行文件 逆向工程 工具

* `Windows`的`PE`格式的`exe文件`、`dll文件`
    * `OllyDBG`
    * `IDA PRO`
        * 二进制分析
    * `Hiew`
        * 反汇编 + 16进制编辑器
        * 命令行，无GUI
* `Linux`的`ELF`格式的文件
    * `GDB`
    * `IDA PRO`
    * `Hopper`
        * Disassembler + Pseudo C decompiler
    * `Evan's debugger`
        * Linux中类似于OllyDBG的工具
    * `Insight`
        * GDB的GUI
        * 有点过时了
* `Mac`的`MACH-O`格式的文件
    * `Hopper`
    * `IDA PRO`
    * `LLDB`
    * `MachOView`
* `Android`的`dex`格式的文件（apk文件内的）
    * `APK TOOL`
        * Disassembler and Assembler (SMALI)
    * `JEB`
        * Android disassembler (SMALI) and decompiler (JAVA)
    * IDA PRO
* `iOS`的可执行文件
    * `IDA Pro`
    * `Hopper`
    * `otool`

TODO：

【未解决】Mac中有哪些常用的破解逆向方面的工具软件

