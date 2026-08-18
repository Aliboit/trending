### omlx — Apple Silicon 专用 LLM 推理服务器

**一句话总结**：为 Apple Silicon 优化的 LLM 推理服务器，支持连续批处理与 SSD 分层 KV 缓存，菜单栏即可管理。

**解决什么问题**：本地 LLM 服务器往往在「便捷」与「控制」之间二选一——oMLX 让常用模型常驻内存、重模型按需换入换出、上下文限制可配置，且全部从 macOS 菜单栏管理。

**核心亮点**
- KV 缓存跨内存热层 + SSD 冷层持久化，即使对话中途上下文变化也可复用
- 连续批处理（continuous batching）提升本地推理吞吐
- 与 Claude Code 等工具配合，让本地 LLM 真正可用于日常编码

**github链接地址**：https://github.com/jundot/omlx
