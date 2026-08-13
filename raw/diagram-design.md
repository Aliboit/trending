### diagram-design — 面向 AI 编码工具的编辑级图表技能

**一句话总结**：一套为 Claude Code 等 AI 编码工具设计的编辑级图表技能，用自包含 HTML+SVG 输出高质量结构图，告别 Mermaid 噪音。

**解决什么问题**：AI 生成的图表通常充斥着 Mermaid 风格的粗糙圆角框和随意配色，设计师不满意、产品不专业。该项目提供多种语义化视觉类型，让 Agent 直接产出出版级的架构图、流程图和系统模式图。

**核心亮点**
- 语义模式将行为描述与布局分离，队列、策略追踪、信任边界可复用现有类型，无需扩展类型数量
- 支持 Claude Code、Codex、Pi 多个 Agent 平台，可将 draw.io / Mermaid 源重绘为指定格式
- 默认静态 HTML 输出，可选无障碍动效，零依赖、零 Figma

**github链接地址**：https://github.com/cathrynlavery/diagram-design
