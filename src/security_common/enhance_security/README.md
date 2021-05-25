# 正向安全

* 正向安全 防护手段
  * 混淆
    * Android
      * 加入 花指令
        * 用于干扰的垃圾代码
    * Mac
      * iOS
        * OC的混淆
  * Android 和 Windows
    * 加壳
      * 加固=防护 的一种手段
      * 不同系统=平台
        * Windows
          * vmprotect
            * 强壳
          * Linux
            * upx
          * Android
          * Mac
            * App Store的ipa
  * Android
    * SO的保护
      * 是什么
        * APP的核心（认证逻辑，加密等）算法采用C/C++编写并编译为SO文件
      * 目的 = 为何要SO防护
        * 增加被破解=反编译的难度
          * 增加黑客利用其业务的难度
      * 优势
        * SO中为原生ARM汇编，难以还原原始代码
          * 对比：DEX文件很容易被各种反编译工具直接还原成通俗易懂的Java代码
        * SO调试成本高
          * 对比：Java写的程序更容易被调试
            * 如使用SmaliIdea、Jeb、IDA、Xposed、插桩打日志等多种方式
        * SO难以在x86生产环境中黑盒调用
          * 对比：DEX文件可转换成class文件，在生产环境中使用JNI直接传参调用
      * 手段
        * 反调试
        * 区块加密
        * `OLLVM`混淆
          * `OLLVM`混淆是逆向人员的噩梦，这招确实能有效提高`so`代码的安全性
            * 破解手段
              * `unicorn`
        * ARM VMP
          * ARM VMP 兼容性问题比较多，还无法商业化
