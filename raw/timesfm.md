### timesfm — Google 时间序列基础模型

**一句话总结**：Google Research 发布的预训练时间序列基础模型，用于通用时间序列预测任务。

**解决什么问题**：传统时间序列预测通常需要针对每个业务场景单独建模和调参，在企业 SQL、表格、端点服务和自动化调用场景中复用成本高。

**核心亮点**
- 基于 ICML 2024 论文的 decoder-only 时间序列基础模型，提供 Hugging Face checkpoints
- 最新版本为 TimesFM 2.5，并保留 1.0、2.0 等历史版本代码与安装方式
- 已关联 BigQuery ML、Google Sheets、Vertex Model Garden 等产品化使用场景

**github链接地址**：https://github.com/google-research/timesfm
