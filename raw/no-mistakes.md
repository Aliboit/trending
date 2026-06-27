### no-mistakes — git push 前的 AI 驱动验证门禁

**一句话总结**：no-mistakes 是一个 git push 代理，在代码真正推送前用 AI 驱动的验证流水线清理问题并生成 PR。

**解决什么问题**：开发者和 AI 编程 Agent 很容易把未充分验证、风格混乱或存在隐患的代码直接推到远端；该工具把 push 变成异步门禁流程，在隔离 worktree 中先检查、修复和升级问题。

**核心亮点**
- 在本地远端代理前运行，不阻塞当前工作区，使用一次性 worktree 完成验证。
- 支持 claude、codex、opencode、copilot 等多种 Agent 或 acp 目标，Agent 无关。
- 通过自动修复、问题升级和 PR 创建，把"人类最终负责"与"AI 自动把关"结合起来。

**github链接地址**：https://github.com/kunchenguid/no-mistakes
