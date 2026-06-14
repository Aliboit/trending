### agentsview — 本地优先的 AI 编码 Agent 会话与成本分析工具

**一句话总结**：本地优先的 AI 编码 Agent 会话浏览与成本分析工具，号称比 ccusage 快 100 倍。

**解决什么问题**：使用 Claude Code、Codex 等 20+ 编码 Agent 后，会话散落各处、token 花费难统计，本工具一站式聚合到本地 SQLite 并用 Web UI 浏览。

**核心亮点**
- 单二进制、零账号、纯本地，自动发现各 Agent 的会话目录
- 提供 Web UI 与 `usage daily` CLI，按天/按 Agent 看成本
- 默认绑定 loopback 并校验 Host 头，防 DNS rebinding，对远程开发友好

**github链接地址**：https://github.com/kenn-io/agentsview
