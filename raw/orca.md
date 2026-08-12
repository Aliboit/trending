### Orca — 并行 Agent 编排器

**一句话总结**：并行 Agent 编排器，用一个提示词扇出到多个编码代理（Codex/ClaudeCode/OpenCode/Pi），各自独立 worktree，统一跟踪管理。

**解决什么问题**：开发者想并行运行多个 AI 编码代理但缺乏统一管理，Orca 让每个代理在独立 git worktree 中工作，可比较结果并合并最优方案。

**核心亮点**
- 手机端伴侣 App（iOS/Android），随时随地监控和操控 agent
- Ghostty 级终端分屏 + WebGL 渲染，无限分屏、重启后保留 scrollback
- 设计模式：点击 UI 元素自动发送 HTML/CSS/截图到 agent

**github链接地址**：https://github.com/stablyai/orca
