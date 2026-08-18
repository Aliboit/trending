### ai-memory — AI 编码 Agent 的跨厂商长期记忆方案

**一句话总结**：为 AI 编码 CLI 提供长期记忆，让不同厂商的 Agent 在同一目录下无缝交接。

**解决什么问题**：中途退出 Claude Code 换 OpenAI Codex 后，新 Agent 对架构、失败尝试和待办问题一无所知——ai-memory 把这些上下文持久化，跨厂商延续。

**核心亮点**
- 支持跨 Agent 供应商交接（Claude Code ↔ Codex 等），无需重复解释项目背景
- 提供 Linux/macOS 原生二进制、Docker 镜像及 systemd 单元，部署方式齐全
- 面向「agent coding CLI」场景设计，专注开发者日常工作流

**github链接地址**：https://github.com/akitaonrails/ai-memory
