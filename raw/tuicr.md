### tuicr — Vim 键位终端代码审查工具，支持 GitHub/GitLab 导出

**一句话总结**：终端原生代码审查工具，Vim 键位操作，支持 GitHub/GitLab 实时 Review 推送和剪贴板导出。

**解决什么问题**：终端开发者做 Code Review 时缺乏顺手的 TUI 工具。tuicr 提供 GitHub 风格的连续 diff 流，可在行/范围/文件/Review 级别添加评论，并直接推送到 GitHub 或 GitLab。

**核心亮点**
- 支持 git、jj（Jujutsu）和 Mercurial，可审查未提交改动、提交范围或任意 PR/MR
- 审查进度按文件/hunk 粒度持久化，跨会话恢复
- 三种导出目标：GitHub/GitLab 真实 Review、Markdown 到剪贴板、stdout 管道

**github链接地址**：https://github.com/agavra/tuicr
