# LLDB

* `LLDB`
  * =`LLDB Debugger`
  * 是什么：调试器
  * 背景
    * LLVM项目
      * 旗下有多个组件=功能模块
        * 其中有个`调试器` = LLDB Debugger
  * 一句话描述：一个新一代的高性能的调试器
    * a next generation, high-performance debugger
  * 与之相关
    * 编译器：`Clang`
    * 反汇编器：`llvm disassembler`
  * 应用
    * Mac中XCode的默认的调试器
      * 支持语言：`C`, `Objective-C`和`C++`
      * 支持平台：`Mac`和`iOS`
  * 支持众多平台和系统
    * ![lldb_support_arch_platforms](../../../../assets/img/lldb_support_arch_platforms.png)
  * 常见命令举例
    * `run`
    * `break set -n main`
    * `bt`
    * `register read`
    * `di -n main`
  * 资料
    * 官网
      * LLDB Homepage — The LLDB Debugger
        * http://lldb.llvm.org
    * 教程
      * Tutorial — The LLDB Debugger
        * https://lldb.llvm.org/use/tutorial.html
    * LLDB和GDB命令对比
      * GDB to LLDB command map — The LLDB Debugger
        * https://lldb.llvm.org/use/map.html

