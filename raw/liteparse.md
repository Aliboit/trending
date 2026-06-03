### liteparse — 纯本地 OSS 文档解析器

**一句话总结**：LlamaIndex 团队推出的纯本地 OSS 文档解析器，无需 LLM、无需云端，快速提取 PDF 文本 + 坐标框。

**解决什么问题**：很多文档解析工具依赖云端 LLM 或付费 API。LiteParse 全程本地运行，用 PDFium + OCR 给出精确的空间文本布局，零外部依赖。

**核心亮点**
- PDFium C 库提取文本 + 可选 OCR（内置 Tesseract，零配置；也支持 HTTP OCR 服务器）
- 多语言绑定：Rust / Node.js / Python / WASM（浏览器端运行），输出 JSON + Text + 截图
- 流程图式的清晰管线：输入格式 → Rust Core（转换 / 提取 / OCR / 合并 / 投影）→ 输出

**github链接地址**：https://github.com/run-llama/liteparse
