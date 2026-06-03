# headroom

> AI Agent 上下文压缩层，在送到 LLM 之前把 token 压掉 60-95%。

## 解决什么问题

AI Agent 的工具输出、日志、RAG 检索结果往往极为冗长，大量 token 被浪费在无关内容上，导致成本飙升和上下文窗口溢出。

## 核心亮点

- 6 种压缩算法（JSON SmartCrusher / AST CodeCompressor / 文本 Kompress-base），按内容类型自动路由
- 可逆压缩（CCR）：原文本地保存，LLM 按需回调获取，不丢信息
- 一行命令 wrap 已有 Agent（`headroom wrap claude`），或零代码改动启动代理（`headroom proxy`），还提供 MCP Server

## 相关链接

- GitHub: https://github.com/chopratejas/headroom
- 语言: Python
- 首次上榜: 2026-06-03
