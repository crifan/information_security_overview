# Web安全

此处整理和Web网络相关的安全相关知识。

* `Web安全`
  * 根据攻防角度分
    * 进攻
      * 名字和概念
        * `漏洞扫描`
          * `端口扫描`
        * `Web攻击`=`Web漏洞攻击`
        * `Web挖掘`=`Web漏洞挖掘`
        * `Web渗透`
      * 攻击方式
        * `SQL注入`
        * `跨站 XSS`
        * `CSRF`
        * `越权`
        * `文件包含`
        * `文件上传`
        * `命令执行`
        * `WAF绕过`
        * `URL跳转`
        * `钓鱼`
        * `社工`=`社会工程学`
    * 防守
      * `代码审计`=`安全代码审计`=`安全审计`
        * 目的：写出高质量的漏洞少的代码
      * `日志分析`=`日志关联分析`
        * `深度包检测`
      * 程序行为监视
      * 防护设备
        * 防火墙
          * `WAF`=`Web应用程序防火墙`
        * `IDS`=`Intrusion Detection Systems`=`入侵检测系统`
        * `IPS`=`Intrusion Prevention Systems`=`入侵防御系统`
  * 相关组织和标准
    * 组织：`OWASP`
      * 标准：`OWASP10`
  * 常见方向和工具
    * 漏洞扫描类
      * `AppScan`：IBM的一款安全扫描软件
      * `AWVS`：一款知名的网络漏洞扫描工具
      * `Burp Suite`：一款信息安全从业人员必备的集成型的Web渗透测试工具，价格昂贵的收费软件
      * `Cobalt Strike`：一款基于java的渗透测试神器，常被业界人称为CS神器
      * `Nessus`：目前全世界最多人使用的Web漏洞扫描与分析软件
      * `NetSparker`：一款综合型的web应用安全漏洞扫描工具
      * `Nikto`：一个开源的Web服务器扫描器，漏洞扫描神器
      * `WebScarab`：一个用来分析使用HTTP和HTTPS协议的应用程序框架
      * `Whisker`：一款非常好的HTTP服务器缺陷扫描软件，基于libwhisker
      * `ZAP`：OWASP的集成渗透测试和漏洞工具，免费开源跨平台
    * 端口扫描
      * `nmap`：网络端口扫描嗅探工具
    * SQL注入
      * `Sqlmap`：数据库注入神器
  * 主要工作方向和内容
    * 渗透测试
    * 漏洞挖掘
    * 安全开发
    * 代码审计
    * 网络安保
