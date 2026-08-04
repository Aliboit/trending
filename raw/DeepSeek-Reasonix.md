### DeepSeek-Reasonix — 专为 DeepSeek 模型优化的终端 AI 编码 Agent

**一句话总结**：专为 DeepSeek 模型优化的终端 AI 编码 Agent，以配置与插件驱动，围绕 prefix-cache 稳定性调优以降低长会话 token 成本。

**解决什么问题**：通用 AI 编码 Agent 在长会话中 token 消耗大、缓存命中率低，缺乏针对 DeepSeek 模型特性的深度优化，导致成本不可控。

**核心亮点**
- 单一静态 Go 二进制，配置驱动（reasonix.toml），无硬编码模型
- 支持多模型组合，可双模型分会话运行（executor + planner），各自保持缓存稳定
- 插件驱动架构，外部工具以子进程方式运行，扩展性强

**github链接地址**：https://github.com/esengine/DeepSeek-Reasonix
