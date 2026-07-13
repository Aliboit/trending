### destructive_command_guard — 阻止 AI 编程代理执行危险命令的高性能钩子

**一句话总结**：一个高性能钩子工具，在 AI 编程代理执行危险命令前将其拦截，防止误删代码和文件。

**解决什么问题**：AI 编程助手（如 Claude Code、Cursor、Codex CLI 等）在自动执行终端命令时，可能意外运行 `rm -rf`、`git push --force` 等破坏性命令，导致代码丢失或仓库损坏。该工具在命令执行前进行拦截和校验。

**核心亮点**
- 支持 Claude Code、Codex CLI、Gemini CLI、Copilot CLI、Cursor、Hermes Agent、Grok 等十余种 AI 编程工具
- 基于 Rust 实现，性能极高，不影响代理响应速度
- 一键安装（curl 脚本），配置简单，覆盖 git 和 shell 两类危险命令

**github链接地址**：https://github.com/Dicklesworthstone/destructive_command_guard
