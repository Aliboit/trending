### needle — 14MB 超小型边缘设备基础模型

**一句话总结**：Needle 2 是一个仅 14MB 的超小型基础模型，专为手机、可穿戴、智能家居和机器人等微型设备设计，支持工具调用与结构化提取。

**解决什么问题**：边缘设备上运行 AI 模型受内存和存储严格限制。Needle 2 以 14MB 单二进制、28MB RAM 即可完成完整推理会话，在基准测试中与 FunctionGemma 270M、LFM2.5 230M 互有胜负，体积却小 5-70 倍。

**核心亮点**
- 45M 参数、CQ2-bit 量化，权重直接嵌入引擎二进制，无需额外构建
- 支持工具调用（function calling）、设备交互和结构化提取
- pip 一键安装，推理引擎从 HuggingFace 拉取并缓存

**github链接地址**：https://github.com/cactus-compute/needle
