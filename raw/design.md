# google-labs-code/design.md

**一句话总结**：DESIGN.md 试图成为 AI 编码时代的设计系统说明书，让 Agent 在生成界面时遵循明确的品牌与视觉规则。

**解决什么问题**：传统设计系统通常散落在 Figma、文档和代码中，AI Agent 很难稳定理解颜色、字体、间距、圆角以及背后的设计意图；该规范用 YAML front matter 提供机器可读 token，再用 Markdown 解释设计原则，降低 AI 生成界面时的风格漂移。

**核心亮点**：
- 结合结构化设计 tokens 与自然语言设计 rationale，兼顾机器执行和人类理解。
- 面向 coding agents 的持久上下文文件，可随仓库一起版本化和复用。
- 适合将品牌视觉、组件风格和交互语气沉淀为可被 AI 持续读取的规范。

**GitHub 链接**：https://github.com/google-labs-code/design.md
