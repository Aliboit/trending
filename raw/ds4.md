### ds4 — Redis 作者 antirez 打造的 DeepSeek V4 本地推理引擎

**一句话总结**：Redis 作者 antirez 打造的 DeepSeek V4 本地推理引擎，支持 Metal/CUDA/ROCm，自包含且极致轻量。

**解决什么问题**：通用 GGUF 推理器对特定模型优化不足，缺乏面向 DeepSeek V4 深度调优的本地原生推理方案。

**核心亮点**
- 专为 DeepSeek V4 Flash 优化，同时支持 GLM 5.2 与 DeepSeek V4 PRO
- 支持 Metal（Mac 96GB+）、NVIDIA CUDA（多卡/DGX Spark）、ROCm（Strix Halo）
- 自包含设计，模型加载、Prompt 渲染、工具调用、KV 状态、HTTP 服务与编码 Agent 一体化测试

**github链接地址**：https://github.com/antirez/ds4
