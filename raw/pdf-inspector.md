### pdf-inspector — Rust 编写的快速 PDF 分类与文本提取库

**一句话总结**：用 Rust 编写的快速 PDF 分类与文本提取库，能智能判断 PDF 是否需要 OCR，将约 54% 的文本型 PDF 在 200ms 内完成本地处理。

**解决什么问题**：传统 PDF 处理流程对所有文档一律走 OCR，既慢又贵，而大量 PDF 本身就含可提取文本，无需 OCR 即可高效处理。

**核心亮点**
- 10-50ms 内完成智能分类（文本型/扫描型/图片型/混合型），返回置信度与逐页 OCR 路由建议
- 位置感知的文本提取，支持字体信息、X/Y 坐标与多栏自动排序
- 输出干净 Markdown，提供 Python、Node.js 与 WebAssembly 绑定

**github链接地址**：https://github.com/firecrawl/pdf-inspector
