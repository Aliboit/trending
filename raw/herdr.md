### herdr — 终端agent多路复用器

**一句话总结**：终端原生的 agent 多路复用器，让你在一个终端里并行跑多个编码 agent。

**解决什么问题**：同时跑多个 AI agent（Claude Code、Codex 等）需要开多个窗口、难以统揽全局；该工具像"为 agent 重建的 tmux"。

**核心亮点**
- 每个 agent 拥有真实终端，连全屏 TUI 都能正常渲染
- 一眼看清谁在阻塞、谁在工作、谁已完成，支持分屏与标签
- 单个本地 Rust 二进制，无 GUI、无 Electron、无账号、无遥测

**github链接地址**：https://github.com/ogulcancelik/herdr
