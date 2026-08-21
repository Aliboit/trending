### substrate — 面向大规模 Agent 部署的高密度运行时

**一句话总结**：Agent Substrate 核心系统，面向大规模 Agent 部署的高密度运行时。

**解决什么问题**：提供高性能、高密度的 Agent 运行环境，实现亚秒级 Agent 恢复/挂起与大量 Agent 在同一基础设施上的复用。

**核心亮点**
- 控制平面提供 Agent 沙箱的全生命周期管理
- 支持 microVM 与 gVisor 等多种沙箱技术
- 将大量"actor"映射到少量"worker"，提升资源利用率

**github链接地址**：https://github.com/agent-substrate/substrate
