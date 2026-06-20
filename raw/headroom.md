### headroom — AI Agent 上下文压缩层

**一句话总结**：一个面向 AI agent 的上下文压缩层，可在不显著损失答案质量的情况下减少 60–95% token。

**解决什么问题**：代理读取日志、工具输出、RAG 片段和长文件时会快速耗尽上下文窗口并增加成本；Headroom 在内容进入 LLM 前进行本地优先、可逆或可控压缩。

**核心亮点**
- 覆盖工具输出、日志、文件、RAG chunks 与对话历史等多类输入。
- 提供库、代理、MCP server 等形态，并内置 6 种压缩算法。
- 强调 local-first 与可逆压缩，适合嵌入现有 agent 工作流以节省上下文预算。

**github链接地址**：https://github.com/chopratejas/headroom
