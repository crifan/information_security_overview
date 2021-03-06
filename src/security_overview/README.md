# 安全概览

## 背景

先说说写这个教程的背景：

* 之前已写过 安卓安全和破解 的教程
    * https://github.com/crifan/android_app_security_crack
        * 目前点赞不少 500+个star
        * 看来大家比较关注这个领域
* 自己计划从事`计算机安全领域`
    * 之前是小白，没这方面的经验
    * 打算边自学，边总结，总结到这个教程中
        * 供自己和他人参考

## 信息安全技术概览

信息安全技术概念包含内容较多，且涉及维度较广，下面以不同维度来阐述，常见分类和对应内容。

* 信息安全
  * 概述
    * ![security_overview_web_desktop](../assets/img/security_overview_web_desktop.jpg)
  * 根据不`同端`=`目标`=`设备`分
    * `Web端`：`网络安全`=`Web安全`=`互联网安全`
    * `设备端`
      * `PC端`：`计算机安全`
        * 包含
          * `Windows`
          * `Mac`
          * `Linux`
      * `移动端`：`移动安全`
        * 包含
          * `Android`
          * `iOS`
      * `IoT端`：`物联网安全`
      * 其他特定设备
        * `WiFi安全`
  * 广义的信息安全
    * 子领域=特殊领域
      * `信息存储安全`
        * 典型应用场景：指纹、虹膜、信用卡PIN码等
        * 包含
          * 硬件
            * `TrustZone`
          * 软件
            * `OP-TEE`