### computer — Cloudflare 推出的虚拟文件系统，给 AI Agent 一台电脑

**一句话总结**：Cloudflare 推出的"给 Agent 一台电脑"虚拟文件系统，让 AI Agent 拥有持久化、可执行的真实计算环境。

**解决什么问题**：AI Agent 缺少一个持久、可控、可执行的"工作空间"。Cloudflare Computer 把虚拟文件系统放进 Durable Object（SQLite 权威状态），并提供三种可插拔执行后端：容器（FUSE 挂载真实 Linux 用户态）、Isolate shell（bash）、Isolate JavaScript（ESM 模块），让 Agent 能真正"动手"操作文件与运行代码。

**核心亮点**
- 三种执行后端：Container（沙箱容器 + 真实 Linux 用户态）、Isolate shell、Isolate JavaScript，覆盖不同隔离与能力需求
- 状态权威存储在 Durable Object 的 SQLite 中，沙箱侧通过 computerd 守护进程 capnweb RPC 双向同步
- 天然适配 Cloudflare Workers 生态，低延迟全球边缘执行

**github链接地址**：https://github.com/cloudflare/computer
