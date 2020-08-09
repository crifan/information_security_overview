# LLVM

* `LLVM`
  * =`Low Level Virtual Machine`
  * 是什么=一句话描述
    * 一套用于构建出高度优化的编译器、优化器、运行环境的工具集合
      * a toolkit for the construction of highly optimized compilers, optimizers, and runtime environments.
  * 主要包含3个部分
    * `LLVM套件`=`LLVM Suite`
      * 包含各种
        * 工具
          * `汇编器`=`assembler`
          * `反汇编器`=`disassembler`
          * `位码分析器`=`bitcode analyzer`
          * `位码优化器`=`bitcode optimizer`
          * 简单的回归测试
            * 用于测试LLVM工具和Clang前端
        * 库
        * 头文件
    * `Clang`=`Clang前端`=`Clang front end`
      * 是什么：LLVM的内置的原生的`C`/`C++`/`Objective-C`编译器
      * 可以把`C`, `C++`, `Objective-C`和`Objective-C++`的代码，编译成`LLVM bitcode`
        * 然后就可以用LLVM套件去操作此（编译后的）程序了
    * `测试套件`=`Test Suite`
      * 一堆工具的集合
        * 测试LLVM的功能和性能
  * 子项目
    * `LLVM Core` libraries
      * a modern source- and target-independent optimizer, along with code generation support for many popular CPUs
    * `Clang`
      * an `LLVM native` C/C++/Objective-C compiler
    * `LLDB`
      * a great native debugger
        * 基于`LLVM`和`Clang`
    * `libc++`和`libc++ ABI`
      * a standard conformant and high-performance implementation of the C++ Standard Library
        * including full support for C++11 and C++14
    * `compiler-rt`
      * provides highly tuned implementations of the low-level code generator
    * `MLIR`
      * a novel approach to building reusable and extensible compiler infrastructure
    * `OpenMP`
      * an OpenMP runtime for use with the OpenMP implementation in Clang
    * `polly`
      * a suite of cache-locality optimizations as well as auto-parallelism and vectorization using a polyhedral model
    * `libclc`
      * implement the OpenCL standard library
    * `klee`
      * implements a "symbolic virtual machine" which uses a theorem prover to try to evaluate all dynamic paths through a program in an effort to find bugs and to prove properties of functions
    * `LLD`
      * a new linker
        * a drop-in replacement for system linkers and runs much faster
  * 资料
    * 官网
      * The LLVM Compiler Infrastructure Project
        * https://llvm.org
    * 快速上手
      * Getting Started with the LLVM System — LLVM 12 documentation
        * https://llvm.org/docs/GettingStarted.html
  * 相关
    * 概念
      * `IR`=`Intermediate Representation`=`中间表示层`
