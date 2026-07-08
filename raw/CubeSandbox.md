### CubeSandbox — 面向 AI Agent 的轻量安全沙箱服务

**一句话总结**：基于 RustVMM 和 KVM 构建的高性能安全沙箱，专为 AI Agent 提供即时、并发、隔离的代码执行环境。

**解决什么问题**：AI Agent 执行不可信代码需要安全隔离环境，传统容器开销大、启动慢，难以支撑高并发。

**核心亮点**
- 60ms 内创建硬件隔离沙箱，内存开销低于 5MB
- 兼容 E2B SDK，支持单节点与多节点集群弹性扩展
- v0.5 新增 AutoPause/Resume、Terraform 一键部署、ARM64 原生支持

**github链接地址**：https://github.com/TencentCloud/CubeSandbox
