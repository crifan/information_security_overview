# TrustZone
* `TrustZone`
  * ARM
    * 提出了TrustZone技术
    * 为了确保数据安全
    * 用一根`安全总线`（称为`NS`位）来判断当前处于`secure world`还是`non-secure world`状态
        * 状态的切换由`ATF`=`ARM Trusted Firmware`来完成