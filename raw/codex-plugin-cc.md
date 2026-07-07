### codex-plugin-cc — Claude Code中调用Codex的官方插件

**一句话总结**：OpenAI 官方插件，让 Claude Code 用户直接调用 Codex 做代码审查或委派任务。

**解决什么问题**：用户想在熟悉的 Claude Code 工作流中借助 Codex 的能力，但缺乏统一入口；该插件补齐了跨模型协作的桥接。

**核心亮点**
- /codex:review、/codex:adversarial-review 等命令，支持对抗式审查
- 可委派任务、跨会话交接、管理后台作业（rescue/transfer/status）
- ChatGPT 订阅即可用，无需额外 API key（亦支持 API key）

**github链接地址**：https://github.com/openai/codex-plugin-cc
