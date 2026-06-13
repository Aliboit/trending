### LMCache — LLM 推理 KV 缓存加速层

**一句话总结**：可扩展 LLM 推理的 KV 缓存管理层，加速大模型上下文复用。

**解决什么问题**：长上下文与高并发场景下 KV Cache 计算与显存压力巨大，缺乏跨实例共享与分层缓存方案。

**核心亮点**
- 已加入 PyTorch 基金会，并被 NVIDIA Dynamo 集成用于 LLM 推理加速
- 多节点 P2P CPU 内存共享、新多进程架构等持续演进
- 在 AMD MI300X 等新硬件上提供智能体工作负载基准

**github链接地址**：https://github.com/LMCache/LMCache
