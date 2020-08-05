# radare2

* radare2
  * 是什么：著名的开源逆向工具
    * Unix-like reverse engineering framework and commandline tools
  * 竞品
    * IDA
  * 支持平台
    * Mac
    * Windows
    * Linux
    * Solaris
    * Android
    * iOS
    * Haiku
  * 历史
    * Radare project started as a forensics tool, a scriptable commandline hexadecimal editor able to open disk files
    *  but later support for analyzing binaries, disassembling code, debugging programs, attaching to remote gdb servers
  * 功能：Radare is a portable reversing framework that can
    * Disassemble (and assemble for) many different architectures
    * Debug with local native and remote debuggers (gdb, rap, webui, r2pipe, winedbg, windbg)
    * Run on Linux, *BSD, Windows, OSX, Android, iOS, Solaris and Haiku
    * Perform forensics on filesystems and data carving
    * Be scripted in Python, Javascript, Go and more
    * Support collaborative analysis using the embedded webserver
    * Visualize data structures of several file types
    * Patch programs to uncover new features or fix vulnerabilities
    * Use powerful analysis capabilities to speed up reversing
    * Aid in software exploitation
  * 包含工具
    * `rabin2`: 查看文件格式的
    * `radiff2`: 比较文件不同的
    * `rahash2`: 各种密码算法，hash算法集成
    * `rasm2`: 汇编和反汇编
    * `ragg2`: 开发shellcode工具(radare2自己编写的编译器)
    * `radare2`: 整合了所有工具
  * 资料
    * 官网
      * radare
        * https://rada.re/n/radare2.html
    * GitHub
      * radareorg/radare2: UNIX-like reverse engineering framework and command-line toolset
        * https://github.com/radareorg/radare2

## R2Pipe

R2Pipe是一个可以调用 Radare2的 Python 脚本库

