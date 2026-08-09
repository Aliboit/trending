### ladybird — 真正独立的全新引擎 Web 浏览器

**一句话总结**：一个真正独立的全新引擎 Web 浏览器，不基于 Chromium/Gecko/WebKit，目前处于 pre-alpha 阶段。

**解决什么问题**：现代浏览器引擎被少数巨头垄断（Chromium/Gecko/WebKit），缺乏真正独立、基于 Web 标准从头构建的开源浏览器引擎。

**核心亮点**
- 多进程架构：主 UI 进程 + 多个 WebContent 渲染进程 + ImageDecoder 进程 + RequestServer 进程
- 每个标签页独立沙箱化渲染进程，图像解码与网络连接在进程外执行，增强对恶意内容的防护
- 基于 SerenityOS 核心库（LibWeb 渲染引擎、LibJS 引擎、LibWasm、LibCrypto/LibTLS）

**github链接地址**：https://github.com/LadybirdBrowser/ladybird
