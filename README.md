# GitHub Trending 日报

> 收集 GitHub 每日热度排行榜（Trending）上榜仓库的中文内容简介。

每天从 GitHub Trending 中挑选值得关注的开源项目，用统一的「四段式」中文卡片记录下来：一句话讲清它是什么、解决什么问题、有哪些核心亮点，并附上仓库地址。方便快速浏览、回顾和检索每日热点。

## 目录结构

```
.
├── README.md          # 本文件：项目说明 + 收录索引
└── raw/               # 每个 .md 对应一个上榜仓库的简介卡片
    ├── claude-code.md
    ├── twenty.md
    └── ...
```

`raw/` 下每个文件名对应该 GitHub 仓库名，一个文件就是一张仓库简介卡片。

## 卡片格式

每张卡片统一为以下四段式，便于阅读和后续自动化处理：

```markdown
### 仓库名 — 一句话定位

**一句话总结**：……

**解决什么问题**：……

**核心亮点**
- ……
- ……
- ……

**github链接地址**：https://github.com/owner/repo
```

## 收录索引

目前共收录 **33** 个仓库。

### AI 编码 Agent、技能与插件

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| [claude-code](raw/claude-code.md) | Anthropic 官方终端内 AI 编码代理 | [GitHub](https://github.com/anthropics/claude-code) |
| [superpowers](raw/superpowers.md) | 让 AI 编码代理拥有「超能力」的开发方法论 | [GitHub](https://github.com/obra/superpowers) |
| [compound-engineering-plugin](raw/compound-engineering-plugin.md) | Every 的「复利工程」AI 编码插件 | [GitHub](https://github.com/EveryInc/compound-engineering-plugin) |
| [harness](raw/harness.md) | 一句话自动生成 Claude Code 的 Agent 团队 | [GitHub](https://github.com/revfactory/harness) |
| [ECC](raw/ECC.md) | Agent 性能优化操作系统（黑客松获奖） | [GitHub](https://github.com/affaan-m/ECC) |
| [plugins](raw/plugins.md) | Cursor 官方插件规范与首批官方插件 | [GitHub](https://github.com/cursor/plugins) |
| [knowledge-work-plugins](raw/knowledge-work-plugins.md) | Anthropic 官方 11 个角色化知识工作插件 | [GitHub](https://github.com/anthropics/knowledge-work-plugins) |
| [Anthropic-Cybersecurity-Skills](raw/Anthropic-Cybersecurity-Skills.md) | 754 个生产级网络安全技能，映射五大安全框架 | [GitHub](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) |
| [Understand-Anything](raw/Understand-Anything.md) | 代码知识图谱可视化，一眼看懂代码全局 | [GitHub](https://github.com/Lum1104/Understand-Anything) |
| [headroom](raw/headroom.md) | AI Agent 上下文压缩层，省 60-95% token | [GitHub](https://github.com/chopratejas/headroom) |
| [supermemory](raw/supermemory.md) | 多项基准第一的 AI 记忆引擎 | [GitHub](https://github.com/supermemoryai/supermemory) |

### AI 内容「去 AI 味」（写作 · 设计 · 模型）

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| [stop-slop](raw/stop-slop.md) | 给 AI 写作「去 AI 味」的技能规则 | [GitHub](https://github.com/hardikpandya/stop-slop) |
| [taste-skill](raw/taste-skill.md) | 反「AI 味」的前端设计品味框架 | [GitHub](https://github.com/Leonxlnx/taste-skill) |
| [impeccable](raw/impeccable.md) | 让 AI 做出好看前端的设计语言与命令 | [GitHub](https://github.com/pbakaus/impeccable) |
| [heretic](raw/heretic.md) | 全自动大模型「去审查」工具 | [GitHub](https://github.com/p-e-w/heretic) |

### 大模型 / 机器学习（模型 · 训练 · 课程）

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| [VoxCPM](raw/VoxCPM.md) | 无 Tokenizer 端到端 TTS 模型，支持 30 种语言 | [GitHub](https://github.com/OpenBMB/VoxCPM) |
| [Kronos](raw/Kronos.md) | 首个金融 K 线开源基础模型（AAAI 2026） | [GitHub](https://github.com/shiyu-coder/Kronos) |
| [train-llm-from-scratch](raw/train-llm-from-scratch.md) | 用 PyTorch 从零训练 LLM 的完整教程 | [GitHub](https://github.com/FareedKhan-dev/train-llm-from-scratch) |
| [stable-worldmodel](raw/stable-worldmodel.md) | 可复现的世界模型研究平台 | [GitHub](https://github.com/galilai-group/stable-worldmodel) |
| [production-agentic-rag-course](raw/production-agentic-rag-course.md) | 生产级 Agentic RAG 7 周实战课程 | [GitHub](https://github.com/jamwithai/production-agentic-rag-course) |

### 金融 / 量化交易

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| [TradingAgents](raw/TradingAgents.md) | 多智能体 LLM 金融交易框架 | [GitHub](https://github.com/TauricResearch/TradingAgents) |
| [machine-learning-for-trading](raw/machine-learning-for-trading.md) | 《机器学习算法交易》第二版配套代码 | [GitHub](https://github.com/stefan-jansen/machine-learning-for-trading) |

### 数据采集与文档处理

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| [Scrapling](raw/Scrapling.md) | 自适应、反反爬的 Python 爬虫框架 | [GitHub](https://github.com/D4Vinci/Scrapling) |
| [markitdown](raw/markitdown.md) | 微软万能文件转 Markdown 工具 | [GitHub](https://github.com/microsoft/markitdown) |
| [liteparse](raw/liteparse.md) | LlamaIndex 纯本地文档解析器 | [GitHub](https://github.com/run-llama/liteparse) |
| [docs](raw/docs.md) | GitHub 官方文档开源仓库 | [GitHub](https://github.com/github/docs) |

### 应用 · 平台 · 其他

| 项目 | 简介 | 仓库 |
| --- | --- | --- |
| [MoneyPrinterTurbo](raw/MoneyPrinterTurbo.md) | 一键 AI 短视频生成器 | [GitHub](https://github.com/harry0703/MoneyPrinterTurbo) |
| [twenty](raw/twenty.md) | 开源的 Salesforce 替代品（CRM） | [GitHub](https://github.com/twentyhq/twenty) |
| [project-nomad](raw/project-nomad.md) | 离线优先的自包含知识服务器 | [GitHub](https://github.com/Crosstalk-Solutions/project-nomad) |
| [flowsint](raw/flowsint.md) | 图可视化 OSINT 调查平台 | [GitHub](https://github.com/reconurge/flowsint) |
| [hermes-webui](raw/hermes-webui.md) | Hermes Agent 的三栏式 Web 界面 | [GitHub](https://github.com/nesquena/hermes-webui) |
| [FreeDomain](raw/FreeDomain.md) | 人人可用的免费域名公益项目 | [GitHub](https://github.com/DigitalPlatDev/FreeDomain) |
| [English-level-up-tips](raw/English-level-up-tips.md) | 风靡中文圈的英语学习指南，2026 版加入 AI 方法论 | [GitHub](https://github.com/byoungd/English-level-up-tips) |

## 如何新增一条

1. 在 `raw/` 下新建 `仓库名.md`，文件名与 GitHub 仓库名保持一致；
2. 按上面的「卡片格式」填写四段内容，`github链接地址` 指向该仓库主页；
3. 在「收录索引」中对应分类下追加一行。
