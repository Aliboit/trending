### ktransformers — CPU-GPU 异构 LLM 推理/微调框架

**一句话总结**：专注于通过 CPU-GPU 异构计算实现大语言模型高效推理与微调的研究框架。

**解决什么问题**：大模型推理与微调对显存和算力要求极高，单一硬件难以高效承载，需要异构计算优化方案。

**核心亮点**
- 提供 Inference 和 SFT 两大用户能力，支持 MiniMax-M3、GLM-5.2、DeepSeek-V4-Flash 等 Day0 适配
- 在消费级硬件上实现可用的边缘 Agentic AI 推理性能
- 活跃的 Roadmap（2026Q2）与版本迭代（v0.6.1 刷新 kt-kernel 推理）

**github链接地址**：https://github.com/kvcache-ai/ktransformers
