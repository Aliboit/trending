# train-llm-from-scratch

**一句话总结：** 从下载训练数据到生成文本，用PyTorch从零实现Transformer并训练LLM的完整教程。

**解决什么问题：** 大模型训练对大多数人来说像黑盒，现有教程要么太理论、要么不完整。这个项目提供了端到端的实操路径。

**核心亮点：**
- 基于《Attention is All You Need》论文从零实现完整Transformer架构，代码逐模块讲解
- 支持单GPU训练百万到十亿参数模型，提供各GPU型号的训练能力对照表
- 使用825GB的Pile数据集，附训练Loss曲线和生成文本示例
