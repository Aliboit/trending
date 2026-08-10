### code-graph-rag — 基于知识图谱的多语言 monorepo RAG 查询编辑工具

**一句话总结**：用 Tree-sitter 解析多语言代码库、在 Memgraph 中构建知识图谱，支持自然语言查询与编辑的 monorepo RAG 工具。

**解决什么问题**：大型 monorepo 中多语言代码理解困难，传统检索难以捕捉代码结构和跨文件依赖关系。

**核心亮点**
- Tree-sitter 统一解析多语言，Memgraph 知识图谱统一 schema 描述代码结构
- 支持自然语言查询、编辑优化以及基于 AST 的结构化搜索与替换
- 插件化语言扩展（如 Ruby 仅需一个 YAML 模式文件即可接入）

**github链接地址**：https://github.com/vitali87/code-graph-rag
