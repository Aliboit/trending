### openinterpreter — 低成本模型的编码 Agent

**一句话总结**：OpenAI Codex 的分支，专注于让低成本模型也能跑好编码 Agent，并模拟最优 Agent harness。

**解决什么问题**：顶级编码 Agent 性能依赖昂贵模型，低成本/开源模型直接使用效果差，需要专门优化的 harness 才能发挥潜力。

**核心亮点**
- `/harness` 命令切换多种 harness：native、claude-code、zcode、kimi-cli、qwen-code、deepseek-tui 等
- 内置 QA 技能，让任意模型在真实浏览器中驱动和测试 Web 界面
- 一行命令安装（macOS/Linux/Windows）

**github链接地址**：https://github.com/openinterpreter/openinterpreter
