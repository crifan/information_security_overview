# iOS安全

iOS安全包含很多方面：

* 数据保护
  * 网络数据
  * IPA 资源数据
  * 沙盒数据
    * sqlite
      * sqlite加密
        * SQLCipher
          * https://github.com/sqlcipher/sqlcipher
  * Keychain 数据
* 混淆保护
    * 符号混淆
        * 工具
            * `ios-class-guard`
        * 破解
            * `class-dump`
    * 字符串混淆
    * 指令混淆
        * =？ 代码逻辑混淆
* 反调试保护
  * 常见方式
    * `ptrace`
    * `sysctl`
* 异常检测
  * 越狱设备检测
  * 重签名检测
  * 动态库注入检测
  * 调试检测
  * 钩子检测
* 扫描工具
  * `fortify`
    * 侧重于代码的安全漏洞
  * `coverity`
    * 侧重于代码质量
* 逆向
  * 工具
    * `dumpdecrypted`
    * `Reveal`
    * `Cycript`
  * 高级内容
    * 程序加载
    * `Mach-O`文件格式
    * ARM 汇编
    * hook=钩子
      * 常见方式
        * MethodSwizzle
          * 通过 runtime 交换方法的实现
        * fishhook
          * facebook 开源的一个库
            * facebook/fishhook: A library that enables dynamically rebinding symbols in Mach-O binaries running on iOS.
              * https://github.com/facebook/fishhook
* 破解工具
  * `MonkeyDev`
* 越狱工具
  * `adv-cmds`
    * 执行 ps 命令报错，需要安装这个工具
  * `appsync`
    * 让系统不再验证签名，以免安装应用失败
  * `iFile`
    * 在手机上查看文件目录
  * `Cydia Substrate`
    * 允许第三方开发者在越狱系统的方法中打一些补丁或扩展方法
