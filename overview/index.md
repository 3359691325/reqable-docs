---
sidebar_position: 0
---

# 概览

Reqable是一款跨平台的专业HTTP开发和调试工具，在全平台支持HTTP1、HTTP2和HTTP3(QUIC)，简单易用，功能强大，性能高效，助力程序开发和测试人员提高生产力！

![此处应有图](/img/ic_reqable.png)

### 历史

Reqable的前身是HttpCanary（一款Android平台应用程序），但是我们推翻了所有的技术栈，并用C++和Flutter重写，只保留了Logo，所以两者并没有关联。当然，Reqable的使命之一，就是完全替代HttpCanary。

### 特性

Reqable提供了两大基本功能：**REST**和**Capture**调试，前者用于常规的接口测试，后者提供更专业地对HTTP网路测试功能，两者相辅相成。

#### 1. REST

编辑并发送HTTP请求，用来测试接口和获取结果。

- [x] 支持HTTP/1.1, HTTP2和HTTP3(QUIC)协议版本。
- [x] 支持Json/Text/Urlencode/Multiparts/Binary多数据类型，以及文件拖拽。
- [x] 支持JSON/XML/图片/HEX/Multiparts等多种视图，数据浏览更方便。
- [x] URL语法高亮和多行显示，对超长的URL非常友好。
- [x] Header编辑具有自动提示功能，以及超赞的批量编辑。
- [x] Cookie管理，自动保存Cookie并在请求头中自动加入关联的Cookie。
- [x] cURL导入和导出，在同事之间快速分享REST请求。
- [x] 请求授权设置，支持API KEY、Basic Auth和Bearer Token。
- [x] Web代理设置，支持自定义代理配置，也支持系统代理。

#### 2. Capture

通过Web中间人代理的方式对本机以及局域网设备进行数据抓包和修改测试。

- [x] 支持HTTP/1.x, HTTP2协议版本，HTTP3(QUIC)暂不支持。
- [x] 支持HTTPs，TLSv1.1、TLSv1.2和TLSv1.3。
- [x] 搜索和筛选：提供快捷筛选栏和多条件高级搜索。
- [x] 网关功能：对指定请求或响应进行屏蔽，挂起等操作。
- [x] 重写功能：预设规则对指定请求或响应进行替换或者修改。
- [x] 断点功能：对请求或响应进行实时断点操作，比如屏蔽，挂起或修改替换数据等。
- [x] 脚本功能：支持编写Python脚本处理请求或响应。
- [x] 镜像功能：对指定域名配置镜像。
- [ ] 对比功能：Diff两个请求或相应（规划中）。
- [x] 更多功能：重发，高亮、HAR导入导出等。
