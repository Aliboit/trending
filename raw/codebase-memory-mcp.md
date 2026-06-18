### codebase-memory-mcp — AI 编码代理代码智能引擎

**一句话总结**：一个把代码库快速索引成知识图谱、供 AI 编码代理低成本查询的 MCP 代码智能引擎。

**解决什么问题**：大型代码库对 AI Agent 来说上下文昂贵且检索效率低，传统全文读取会浪费大量 token，也难以准确理解函数、类、调用链和跨服务关系。

**核心亮点**
- 支持 158 种语言的 tree-sitter AST 解析，并对多种主流语言增强 LSP 语义类型解析
- 平均仓库毫秒级索引，结构化查询低于 1ms，可显著减少上下文 token 使用
- 单静态二进制、零依赖，提供 14 个 MCP 工具，便于接入多种编码代理

**github链接地址**：https://github.com/DeusData/codebase-memory-mcp
