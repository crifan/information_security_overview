# otool

* `otool`
  * =`object file displaying tool`
  * 是什么：针对目标文件的展示工具
  * 做什么：用来发现应用中使用到了哪些系统库，调用了其中哪些方法，使用了库中哪些对象及属性
  * 来源：Xcode自带的常用工具
* 相关
  * 比otool更好的：`jtool`
  * `otool`的`GUI`版：`otx`
    * x43x61x69/otx: The Mach-O disassembler. Now 64bit and Xcode 6 compatible.
      * https://github.com/x43x61x69/otx

查看当前otool位置：

```bash
✘ crifan@licrifandeMacBook-Pro  ~  which otool
/usr/bin/otool
```

当前版本：

```bash
✘ crifan@licrifandeMacBook-Pro  ~  otool --version
llvm-otool(1): Apple Inc. version cctools-927.0.2
Apple LLVM version 10.0.1 (clang-1001.0.46.4)
  Optimized build.
  Default target: x86_64-apple-darwin19.2.0
  Host CPU: broadwell

  Registered Targets:
    aarch64    - AArch64 (little endian)
    aarch64_be - AArch64 (big endian)
    arm        - ARM
    arm64      - ARM64 (little endian)
    armeb      - ARM (big endian)
    thumb      - Thumb
    thumbeb    - Thumb (big endian)
    x86        - 32-bit X86: Pentium-Pro and above
    x86-64     - 64-bit X86: EM64T and AMD64
```

## help帮助语法

```bash
✘ crifan@licrifandeMacBook-Pro  ~  otool -help
error: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/otool: unknown char `p' in flag -help

Usage: /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/otool [-arch arch_type] [-fahlLDtdorSTMRIHGvVcXmqQjCP] [-mcpu=arg] [--version] <object file> ...
    -f print the fat headers
    -a print the archive header
    -h print the mach header
    -l print the load commands
    -L print shared libraries used
    -D print shared library id name
    -t print the text section (disassemble with -v)
    -p <routine name>  start dissassemble from routine name
    -s <segname> <sectname> print contents of section
    -d print the data section
    -o print the Objective-C segment
    -r print the relocation entries
    -S print the table of contents of a library (obsolete)
    -T print the table of contents of a dynamic shared library (obsolete)
    -M print the module table of a dynamic shared library (obsolete)
    -R print the reference table of a dynamic shared library (obsolete)
    -I print the indirect symbol table
    -H print the two-level hints table (obsolete)
    -G print the data in code table
    -v print verbosely (symbolically) when possible
    -V print disassembled operands symbolically
    -c print argument strings of a core file
    -X print no leading addresses or headers
    -m don't use archive(member) syntax
    -B force Thumb disassembly (ARM objects only)
    -q use llvm's disassembler (the default)
    -Q use otool(1)'s disassembler
    -mcpu=arg use `arg' as the cpu for disassembly
    -j print opcode bytes
    -P print the info plist section as strings
    -C print linker optimization hints
    --version print the version of /Applications/Xcode.app/Contents/Developer/Toolchains/XcodeDefault.xctoolchain/usr/bin/otool
```
