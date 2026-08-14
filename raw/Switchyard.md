### Switchyard — Rust 编写的 LLM 流量路由代理

**一句话总结**：Rust 编写的 LLM 流量路由代理，跨模型和提供商路由请求，同时保持 OpenAI 与 Anthropic API 原生兼容。

**解决什么问题**：LLM 应用在不同模型和提供商间切换时面临 API 格式不兼容问题。Switchyard 作为代理层，自动翻译 OpenAI Chat、Anthropic Messages、OpenAI Responses 三种格式，让 Claude Code、Codex 等 Agent 直接使用 vLLM、NVIDIA NIM、Ollama 等开源后端。

**核心亮点**
- 协议翻译：OpenAI Chat ↔ Anthropic Messages ↔ OpenAI Responses 无缝转换
- 支持 A/B 基准测试流量分流、信号驱动路由和自定义路由算法
- 记录操作指标，便于成本与性能优化

**github链接地址**：https://github.com/NVIDIA-NeMo/Switchyard
