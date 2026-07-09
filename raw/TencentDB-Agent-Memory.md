### TencentDB-Agent-Memory — 腾讯云AI Agent全本地长期记忆系统

**一句话总结**：为 AI Agent 提供全本地、零外部 API 依赖的长期记忆系统，采用符号化短期记忆 + 分层长期记忆的 4 级渐进管线。

**解决什么问题**：AI Agent 缺乏持久记忆能力，工具日志占用大量 token，碎片化对话难以形成结构化记忆，导致任务成功率低、成本高。

**核心亮点**
- 符号化短期记忆将繁重工具日志压缩为紧凑 Mermaid 符号，集成 OpenClaw 后 token 使用降低最高 61.38%
- 分层长期记忆将碎片化对话蒸馏为结构化角色与场景，而非扁平向量堆叠
- 任务通过率相对提升 51.52%，PersonaMem 准确率从 48% 提升至 76%

**github链接地址**：https://github.com/TencentCloud/TencentDB-Agent-Memory
