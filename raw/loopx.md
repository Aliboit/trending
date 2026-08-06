### loopx — 面向长时运行 AI Agent 的轻量级 loop 工程状态内核

**一句话总结**：面向长时运行 AI Agent 团队的轻量级 loop 工程状态内核，把目标、门禁、待办、证据、配额、交接做到可重启、可复盘。

**解决什么问题**：单个 Agent 跑一个任务容易，但长周期工作难：目标会变、Owner 决策要介入、跨工具与跨 Agent 交接容易丢上下文。LoopX 不替代你的 Agent 运行时，而是提供本地控制平面，让目标、门禁、可执行 todo、证据日志、配额感知自动唤醒、可验证交接保持稳定与可审查。

**核心亮点**
- Agent-loop 无关：兼容 Codex、Claude Code、Cursor 等主流编码 Agent，不绑定特定运行时
- 内置可执行 todos、证据日志、配额感知自动唤醒、可验证交接，让长跑工作可重启可复盘
- 强调"判断权交还人类"，定位为数字员工的管控层而非执行层

**github链接地址**：https://github.com/huangruiteng/loopx
