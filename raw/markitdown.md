### 8. microsoft/markitdown

**一句话总结**：微软出品的万能文件转 Markdown 工具，专为 LLM 文本分析管线设计。

**解决什么问题**：PDF、Word、Excel、PPT、图片、音频等各种格式难以直接喂给 LLM——markitdown 统一转为保留结构的 Markdown，极大提升 AI 处理的便捷性。

**核心亮点**：
- 支持 PDF / PowerPoint / Word / Excel / 图片（OCR）/ 音频（语音转写）/ HTML / EPUB / ZIP / YouTube URL 等十余种格式
- 输出保留标题、列表、表格、链接等结构，主流通用大模型原生"理解" Markdown
- `pip install 'markitdown[all]'` 一行安装，CLI 和 Python API 双模式，支持管道输入
