### celld — 自托管分布式 Durable Objects 守护进程

**一句话总结**：自托管、分布式的 Durable Objects 守护进程，可在自有机器上运行 Cloudflare Workers 和 Durable Objects。

**解决什么问题**：Cloudflare Durable Objects 是强锁定平台服务，开发者希望在自有基础设施上运行类似能力，同时保持分片与持久化特性。

**核心亮点**
- 每个 Object 是独立 SQLite 数据库，按名称寻址并复制到自有 S3 兼容存储桶，天然分片
- 节点仅通过共享存储桶协调，无需控制平面或共识协议，空闲 cell 几乎零资源占用
- 内嵌 V8 执行 Wrangler 打包产物，与 Cloudflare 生态兼容

**github链接地址**：https://github.com/denoland/celld
