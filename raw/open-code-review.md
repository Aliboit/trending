### open-code-review — 阿里开源 AI 代码评审 CLI，确定性管线 + LLM Agent 精确行级评论

**一句话总结**：阿里集团内部打磨两年的 AI 代码评审工具，混合确定性规则管线与 LLM Agent 能力，输出精确到行级的评审意见。

**解决什么问题**：纯 LLM 评审噪音大、漏报多，纯规则评审理解力差。该工具用 agent tool-use 能力读取全文件、搜索代码库，结合内置规则集（NPE、线程安全、XSS、SQL 注入）实现深度评审。

**核心亮点**
- 混合架构：确定性管线 + LLM Agent，兼顾稳定覆盖与上下文理解
- 内置微调规则集：NPE、线程安全、XSS、SQL 注入开箱即用
- 规模验证：两年服务数万开发者、识别百万级缺陷后开源

**github链接地址**：https://github.com/alibaba/open-code-review
