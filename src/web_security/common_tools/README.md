# 常用工具

此处整理Web安全中常用的一些工具

* 工具类
  * 漏洞扫描
      * Burp Suite
          * 
          * 简介
              * 一款信息安全从业人员必备的集成型的渗透测试工具，它采用自动测试和半自动测试的方式
              * 一款专业人员常用的昂贵的工具
          * 特点
              * 收费
              * 有免费的社区版
                  * 但功能有限
              * 功能全面
          * 用途
              * 个人常用于暴破，抓包，CSRF测试等等
      * ZAP
          * `ZAP`=`Zed Attack Proxy`
          * `ZAP`=`OWASP ZAP`
          * 简介
              * 一款开源的Web安全扫描软件
          * 原理
              * ZAP置于浏览器和测试网站之间（又名中间人），允许拦截流量进行检查和修改
          * 竞品
              * Arachni、Wfuzz、Nikto
      * Nessus
          * Burp Suite的竞品
          * Web漏洞扫描程序
      * IBM AppScan
          * IBM公司开发的用于扫描web应用的基础架构，也是安全渗透行业扛把子的产品
      * Whisker
          * Whisker是一款基于libwhisker的扫描器，但是现在大家都趋向于使用Nikto，它也是基于libwhisker的
      * Nikto
          * 一款开源的（GPL）网页服务器扫描器，它可以对网页服务器进行全面的多种扫描
      * Wikto
          * Wikto是一款基于C#编写的Web漏洞扫描工具
      * N-Stealth
          * 现改名为N-Stalker， 是一款商业级的Web服务器安全扫描程序
      * Sn1per
          * 擅长枚举以及扫描已知漏洞
          * 建议这个工具与Metasploit或Nessus一起使用
      * NetSparker
          * 对SQL注入，XSS，LFI等漏洞扫描效果不错的漏洞扫描器
      * `AWVS`
          * =Acunetix Web Vulnerability Scanner
          * 全能的Web安全漏洞扫描器，并附带有很多实用的工具
          * 是一款知名的网络漏洞扫描工具，它通过网络爬虫测试你的网站安全，检测流行安全漏洞
      * cobalt strike
          * =CobaltStrike
          * 一款基于java的渗透测试神器，常被业界人称为CS神器
      * WebScarab
          * WebScarab记录它检测到的会话内容，使用者可以通过多种形式来查看记录
      * Layer
          * 子域名/IP段收集，同时可过滤过出存活主机
      * HP Webinspect
          * 惠普公司的安全渗透产品，运行起来占用大量内存，小家碧玉的就慎用了
      * MSF
  * 端口扫描
      * nmap
          * 不少黑客爱用的工具 ，黑客会利用nmap来搜集目标电脑的网络设定，从而计划攻击的方法
              * Nmap GUI版本：Zenmap
  * `注入`=`SQL注入`
      * Sqlmap
          * 数据库注入神器
          * 自动执行检测、利用SQL注入漏洞并接管数据库服务器的过程
          * 支持
              * MySQL、Oracle、PostgreSQL、Microsoft SQL Server、Microsoft Access、IBM DB2、SQLite、Firebird、Sybase、SAP MaxDB、Informix、HSQLDB和H2
* 操作系统
  * Kali
    * =Kali Linux
    * 旧称：BackTrack Linux
    * 是什么：渗透测试操作系统，自带大量工具
