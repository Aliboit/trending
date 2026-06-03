# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## 语言约定

本仓库项目在 agent 执行过程中（思考、计划、工具说明、进度汇报）和所有面向用户的反馈，**一律使用简体中文**。仓库内的卡片与文档内容也使用简体中文。

## 仓库性质

这是一个**纯 Markdown 内容仓库**，不是代码工程：收集 GitHub 每日热度排行榜（Trending）上榜仓库的中文简介卡片。没有构建、测试、lint 等工具链，也没有任何源码或依赖；所有改动都是在编辑 Markdown 文本。

## 结构与角色

- `raw/<仓库名>.md`：每个文件对应一个上榜 GitHub 仓库，是一张「四段式」简介卡片。**文件名必须与 GitHub 仓库名一致**。
- `README.md`：项目说明 + 「收录索引」。索引按主题分类，每条同时给出指向 `raw/` 卡片和 GitHub 仓库的双链接。**它是 `raw/` 的目录镜像，二者必须保持同步。**
- `UpdatePrompt.md`：用户保存的「更新流程提示词」，描述本仓库的标准维护动作（见下）。

## 卡片格式（强约定）

每张 `raw/*.md` 卡片严格遵循以下四段式，顺序固定：

```markdown
### 仓库名 — 一句话定位

**一句话总结**：……

**解决什么问题**：……

**核心亮点**
- ……
- ……（2-3 条）

**github链接地址**：https://github.com/owner/repo
```

格式细节（保持全仓一致，不要偏离）：
- 段标签用 `**…**：`，**冒号在加粗之外**（不要写成 `**一句话总结：**`）。
- `核心亮点` 标签后不带冒号，紧跟 `-` 列表，2-3 条。
- 标题为单行 `### 仓库名 — 中文定位`；不保留顺序编号、`owner/` 前缀、`⭐ star 数`、`语言/今日Star/首次上榜` 等额外元信息或末尾 `---`。

## 标准维护流程

新增或检查卡片时（即 `UpdatePrompt.md` 描述的任务）：

1. 用 git 提交记录找出新增/改动的 `raw/*.md` 文件。
2. 将其内容整理为上面的四段式格式。
3. 若缺某一段（最常缺 `github链接地址`），按文件名到 GitHub 搜索，取排名第一的同名仓库补全。
4. 同步更新 `README.md` 的「收录索引」（对应分类下增删行）。

## 关键注意事项

- **校验 GitHub 链接时不能只看 star 排序的第一名**：按 star 排序的首位常是同名噪声仓库（例如搜 `claude-code`/`docs`/`plugins` 时首位并非目标仓库）。必须用仓库名精确匹配，并核对 `description` 与卡片内容是否吻合，再写入链接。本环境无 `gh` CLI，可用 GitHub REST 搜索 API（`https://api.github.com/search/repositories`，未认证限 10 次/分）。
