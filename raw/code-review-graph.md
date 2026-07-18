# code-review-graph

**一句话总结**：本地优先的代码智能图，基于 Tree-sitter 构建持久化代码地图，通过 MCP 给 AI 工具精准上下文。

**解决什么问题**：AI 编码工具在 review 任务中反复重读大段代码，浪费 token 且容易遗漏关键改动。

**核心亮点**：
- Tree-sitter 解析 + 增量变更追踪，仅传递"相关切片"
- 一条命令自动检测并配置所有支持的 AI 平台（Claude Code、Cursor 等）的 MCP
- 附带基准测试量化 context 缩减效果，支持多语言文档

**GitHub 链接**：https://github.com/tirth8205/code-review-graph
