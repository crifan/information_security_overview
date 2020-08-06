# Mach-O处理

`Apple`的`Mac`、`iOS`等平台的可执行文件，都是`Mach-O`格式的。

即苹果的可执行文件主要都是`Mach-O`格式的。

现有很多可以处理`Mach-O`格式的工具。

* `Mach-O`
  * =`Mach Object`
  * 文件类型
    * `Executable`=应用=可执行文件
    * `Dylib Library`=动态链接库=`DSO`或`DLL`
    * `Static Library`=静态链接库
    * `Bundle`：不能被链接的Dylib，只能在运行时使用dlopen( )加载，可当做macOS的插件
    * `Relocatable Object File`=可重定向文件
* 相关概念
  * `FatFile`/`FatBinary`
    * 一个由**不同的编译架构**后的`Mach-O`产物所合成的集合体
      * 一个架构的`Mach-O`只能在相同架构的机器或者模拟器上用
        * 为了支持不同架构需要一个集合体
* 常见工具
  * `class-dump`
  * `MachOView`
  * `jtool`
  * `otool`
