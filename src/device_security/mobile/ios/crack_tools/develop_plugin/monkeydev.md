# MonkeyDev

* MonkeyDev
  * 一句话描述：一个基于Xcode模块技术快速开发越狱和非越狱插件的工具，可以自动完成逆向中的固定步骤，一键集成非越狱插件，大大提升逆向分析和开发效率
  * 主要包含模块
    * Logos Tweak
      * 使用theos提供的logify.pl工具将*.xm文件转成*.mm文件进行编译，集成了CydiaSubstrate，可以使用MSHookMessageEx和MSHookFunction来Hook OC函数、C/C++函数或指定地址
    * CaptainHook Tweak
      * 使用CaptainHook提供的头文件进行OC函数的Hook，以及属性的获取
    * Command-line Tool
      * 可以直接创建运行于越狱设备的命令行工具
    * MonkeyApp
      * 自动给第三方应用集成Reveal、Cycript和注入dylib的模块，支持调试dylib和第三方应用，支持Pod给第三方应用集成SDK，只需要准备一个砸壳后的ipa或者app文件即可
    * MonkeyPod
      * 将自动开发的非越狱插件制造成Pod以供其它人通过pod的方法来使用
    * MonkeyAppMac
      * 针对Mac逆向开发的模块，可以自动集成substitute，注入以及符号还原工作
  * 资料
    * Github
      * AloneMonkey/MonkeyDev: CaptainHook Tweak、Logos Tweak and Command-line Tool、Patch iOS Apps, Without Jailbreak.
        * https://github.com/AloneMonkey/MonkeyDev
    * 官网
      * 文档 | MonkeyDev
        * https://monkeydev.org/docs/index.html
