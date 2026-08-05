### ADR — 企业级 AI Agent 安全检测与响应系统

**一句话总结**：企业级 AI Agent 安全系统，覆盖可观测性、安全基准、威胁检测与拦截，已在 Uber 生产部署。

**解决什么问题**：企业内 Cursor/Claude Code/Codex 等编码 Agent 与客服 Agent 大量上线，但其行为不可观测、无安全基准、缺乏威胁检测与拦截。

**核心亮点**
- ADR Observability 跨 macOS/Linux/Windows 捕获 7+ 编码工具的意图/工具调用/执行轨迹
- ADR-Bench 含 300+ 任务、133 个 MCP server，覆盖 17 类 Agent 攻击技术
- 两层检测架构（高召回分诊 + 深度 agentic 推理）+ 防止危险动作，论文已被 MLSys 2026 接收

**github链接地址**：https://github.com/uber/ADR
