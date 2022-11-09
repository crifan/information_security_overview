# 安全概览文字版

* （狭义）信息安全
  * 不同端
    * PC端 vs 移动端
      * PC端
        * 往往指的是 基于浏览器的：[Web安全](https://book.crifan.org/books/avoid_hacker_attack_web_security/website/)
      * 移动端
        * 往往指的是 不同系统和设备的
          * [Android安全](http://book.crifan.org/books/android_app_security_crack/website)
          * [iOS安全](https://book.crifan.org/books/ios_security_protect/website/)
    * 不同类型设备
      * PC端
        * 统称：`计算机安全`=`PC安全`
        * 侧重浏览器、网站等的：**Web安全**
          * 主要攻防方式
            * 攻
              * **渗透攻击**
            * 防
              * [渗透测试](https://book.crifan.org/books/infiltrate_your_net_penetration_testing/website/)
              * **模糊测试**
              * **代码审计**
              * [安全分析](https://book.crifan.org/books/grasp_hacker_track_security_analysis/website/)
                * **安全日志分析**
        * 二进制方面的：[二进制安全](https://book.crifan.org/books/explore_underlying_mechanism_binary_security/website/)
          * Windows
            * **Windows漏洞挖掘**
          * Linux
            * 注：很少有此专门的方向
          * Mac
            * 注：很少有此专门的方向
      * 移动端 = 联网设备方面
        * 相对更广泛的概念：物联网
          * **物联网安全** ~= **工控安全**
        * 侧重某些领域
          * （更接近普通用户的）手机领域：**移动安全**
            * **Android安全**
            * **iOS安全**
          * 工控领域
            * [工控安全](https://book.crifan.org/books/industrial_control_security_overview/website/)
          * 汽车领域
            * [汽车安全](https://book.crifan.org/books/guard_your_car_safety/website/)
          * 无线（设备）领域
            * **无线安全**
              * WiFi领域
                * **WiFi安全**
    * 不同层
      * 上层=Web领域：**Web安全**
      * 底层=内部机制：**二进制安全**
        * Windows的二进制安全
          * **Windows漏洞挖掘**
* （广义）信息安全
  * `信息安全`
  * 子领域=特殊领域
    * `信息存储安全`
      * 典型应用场景：指纹、虹膜、信用卡PIN码等
      * 包含
        * 硬件
          * `TrustZone`
        * 软件
          * `OP-TEE`
    * `功能安全`

## 信息安全各个子方向关键点概述

* 信息安全 各个子方向 关键点概述
  * 安全概述
    * 概念：红方/蓝方、逆向、靶场、蜜罐、漏洞编号、代码审计、日志清理
    * 标准：等级保护、ISO27001
    * 编号：CVE、CNCVE、CNVD
    * 组织：OWASP
    * 比赛：CTF
    * 论坛：看雪、FreeBuf
    * 子领域
      * 存储安全：指纹、虹膜、PIN码、DRM、TrustZone、OP-TEE
      * 密码破解
        * 工具：John the Ripper、Hashcat、Hydra
  * **Web安全**
    * 概念：POC、APT、DDOS、蠕虫、木马、提权、EDR、CSP、Same-Site Cookies、网络劫持、端口扫描、痕迹清理
    * 手段：社工、钓鱼
    * 证书：CISP、CISSP、CISM、CCSRP、CISAW、CISA
    * 系统：Kali
    * 工具和系统：防火墙、WAF、IDS、IPS
  * **渗透测试**
    * 概念：模糊测试、后渗透、测试报告、端口扫描
    * 标准：PTES
    * 手段：XSS、CSRF、文件包含、文件上传、XXE、SQL注入、RCE、SSRF、CORS、越权、struts2漏洞
    * 工具：Metasploit、AppScan、AWVS、BurpSuite、CobaltStrike、Nessus、ZAP、Wikto、nmap、Zenmap、Layer、Sqlmap、Commix、PEACH、Sulley、AutoDafe
  * **代码审计**
    * 工具：CxEnterprise、Armorize CodeSecue、Fortify、RIPS
  * **安全分析** ~= **安全日志分析**
    * 概念：深度包检测(DPI)、态势感知、攻击溯源、网络流量分析、网络扫描、网络取证、流量分析、日志分析、威胁建模分析、安全日志分析、日志关联分析
    * 网络工具：Wireshark、NetworkMiner、Capsa Free、Zenoss Core、The Dude、Angry IP Scanner、
    * 日志处理：ELK、Splunk
  * **二进制安全**
    * 概念：PWN、X86、ARM、汇编、加壳、漏洞挖掘、堆和栈、栈溢出、堆溢出、缓冲区溢出、漏洞分析、漏洞挖掘、病毒分析
  * **Windows漏洞挖掘**
    * 概念：VMProtect、Windows漏洞分析、Windows漏洞挖掘
    * 机制：ASLR、CFG、DEP、GS、SafeSEH、SEHOP、缓冲区溢出、ROP、Heap spray、Shellcode
    * 工具：WinDGB、OllyDBG、IDA、radare2、Hex-rays、dnSpy、Capstone、winchecksec、PEID、EXEinfo PE、Detect It Easy、PEiD、Cheat Engine、MHS、ModifyMemory
  * **移动安全**
    * 概念：代码混淆、代码反混淆、花指令、加壳/加固、去壳/脱壳/砸壳、反调试
  * **Android安全**
    * 概念：反编译、Dalvik、apk、dex、jar、NDK、OLLVM混淆、VMP、Smali/Baksmali、VirtualApp、DroidPlugin、JNI
    * 防护：ProGuard、dep保护、so保护
    * 加固公司：360加固、腾讯乐固legu、爱加密、梆梆安全、顶象安全、几维安全
    * 工具：Apktool、dex2jar、JEB、Xposed、Cydia、Frida、IDA、apkbuilder、FDex2、jadx、DumpDex、Nox夜神模拟器、dex2jar、procyon、CFR、JD-GUI、Luyten、GDA、AndBug、010editor、APK Analyzer、Androguard
  * **iOS安全**
    * 概念：iOS系统安全、mach格式、沙盒、代码签名、越狱
    * 工具：GDB、Hopper Disassembler、LLLVM、LDB、Obfuscator-LLVM、Miasm、lldb-server、radare2、Cutter、ios-class-guard、debugserver、MonkeyDev、class-dump、MachOView、otool、jtool、bfinject、Clutch、Dumpdecrypted、frida-ios-dump、Cydia Substrate、frida、Electra、unc0ver
  * **物联网安全** ~= **工控安全**
    * 安全事件：BlackEnergy
    * 概念：PLC、SCADA、HMI、MTU、RTU、NSE脚本、通信劫持、ATT&CK、固件提取&分析
    * 工控协议：ATG、Modbus、Siemens S7、IEC 104、OPC、PROFIBUS、Profinet、mqtt、zigbee
    * 平台：Shodan、Censys、ZoomEye、FOFA、Diting
    * 固件工具：binwalk、AttifyOS、eimgfs
    * 工控操作系统：Linux、WinCE、FreeRTOS、VxWorks
    * 工控行业：先进制造、电力、轨交、石油石化、烟草、金属钢铁
  * **汽车安全**
    * 技术：V2X
    * 标准： UNECE WP.29、ISO/SAE 21434
  * **无线安全**
    * 无线协议：WiFi、蓝牙、ZigBee、NFC
  * **WiFi安全**
    * 工具：Aircrack-ng、Wifiphisher
