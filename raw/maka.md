### maka — 本地优先的 AI 智能体工作空间

**一句话总结**：Apache 孵化中的本地优先 AI 智能体工作空间。

**解决什么问题**：将模型消息、工具调用、工具结果、权限决策与终止事件记录为可恢复的追加日志，让智能体工作可审计、可重放。

**核心亮点**
- 通过单一 Runtime Host 在本地沙箱边界内运行工具、检视项目
- 所有执行事实以 append-only log 形式落盘，支持审计与恢复
- Apache Incubator PMC 赞助的正式孵化项目

**github链接地址**：https://github.com/apache/maka
