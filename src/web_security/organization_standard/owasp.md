# OWASP10

* 在Web安全领域，有个**组织**叫：
  * `OWASP`
    * =`Open Web Application Security Project`
    * =`开源Web应用安全项目`
    * =`开源Web应用安全组织`
* 该组织每年会推出一个 **标准**：`OWASP 10`
  * OWASP列出了最重要的10个方面的安全攻击
  * 说明
    * 列出排名前10的攻击类型
    * 每年都会出一个报告
      * 最早：2003年
      * 最新：2017年
* 2017年的OWASP 10
  * Injection=注入攻击
    * 涉及方面
      * SQL
          * `SQL Injection`=`SQL注入`
      * NoSQL
      * OS
      * LDAP
          * LDAP Injection
    * 坏结果
      * 运行了不该运行的（恶意的）代码
          * Expression Language (EL) Injection
          * Command Injection
      * 获取了不该获取的数据=盗取数据
    * 心得
      * 编写接受数据的模块时要非常小心
        * 举例
          * `request.getParameter()`
          * `request.getCookie()`
          * `request.getHeader()`
  * Broken Authentication
    * =失效的身份
  * Sensitive Data Exposure
  * XXE
    * XML External Entities
  * Broken Access Control
    * =访问控制缺失
  * Security Misconfiguration
    * =安全配置错误
  * XSS
    * =Cross-Site Scripting
  * Insecure Deserialization
  * Using Components with Known Vulnerabilities
    * =使用含有已知漏洞的组件
  * Insufficient Logging & Monitoring
* 中文主页
  * Welcome to OWASP CHINA — OWASP-CHINA
    * http://www.owasp.org.cn
