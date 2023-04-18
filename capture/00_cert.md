# 证书安装和导出

当使用 HTTPS 协议时，数据在传输过程中被加密，以保护数据的隐私和完整性。当Reqable在使用中间人（MITM）分析HTTPS流量时，需要对服务器下发的SSL证书进行二次构建和签名，因为Reqable自签了一个CA证书且需要被安装到目标设备上。

:::caution

例如：如果通过局域网对移动端设备进行流量分析，SSL证书需要被安装到目标移动端设备上！

:::

### 证书安装

不同平台的SSL证书安装方式各有差异，请根据设备平台选择安装指南：
- [MacOS](/docs/capture/cert_install_macos)
- [Windows](/docs/capture/cert_install_windows)
- [Linux](/docs/capture/cert_install_linux)
- [Android](/docs/capture/cert_install_android)
- [iOS](/docs/capture/cert_install_ios)

### 证书导出

在**[覆写系统代理](proxy)**的前提下，使用浏览器打开下面的链接即可自动下载证书：  
http://proxy.reqable/ssl