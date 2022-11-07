# 设备端安全

TODO：

【未解决】Mac中有哪些常用的破解逆向方面的工具软件

---

和Web网络相对应的，可以统称为 设备端的安全。

主要包括：

* PC端
  * `Windows`
  * `Mac`
  * `Linux`
* 移动端
  * `Android`
  * `iOS`
* `IoT`=物联网设备

下面根据不同维度详细介绍。

## 可执行文件 逆向工程 工具

* `Windows`的`PE`格式的`exe文件`、`dll文件`
  * `OllyDBG`
  * [IDA](https://book.crifan.org/books/reverse_tool_ida/website/)
    * 二进制分析
  * `Hiew`
    * 反汇编 + 16进制编辑器
    * 命令行，无GUI
* `Linux`的`ELF`格式的文件
  * `GDB`
  * [IDA](https://book.crifan.org/books/reverse_tool_ida/website/)
  * [Hopper](https://book.crifan.org/books/ios_re_static_analysis/website/analysis_content/analysis_code_logic/hopper.html)
  * `Evan's debugger`
    * Linux中类似于OllyDBG的工具
  * `Insight`
    * GDB的GUI
    * 有点过时了
* `Mac`的二进制=`iOS`的二进制=`Mach-O`格式的文件
  * [Hopper](https://book.crifan.org/books/ios_re_static_analysis/website/analysis_content/analysis_code_logic/hopper.html)
  * [IDA](https://book.crifan.org/books/reverse_tool_ida/website/)
  * `MachOView`
  * `otool`
  * [LLDB](https://book.crifan.org/books/xcode_debugger_lldb/website/)
* `Android`的`dex`格式的文件（apk文件内的）
  * [apktool](https://book.crifan.org/books/android_re_repack_apk/website/repack_tool/apktool.html)
  * `JEB`
    * Android disassembler (SMALI) and decompiler (JAVA)
  * [IDA](https://book.crifan.org/books/reverse_tool_ida/website/)
