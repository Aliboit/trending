### airllm — 单张 4GB GPU 运行 70B 大模型，无需量化

**一句话总结**：让 70B 大模型在单张 4GB GPU 上推理，无需量化、蒸馏或剪枝。

**解决什么问题**：大模型推理显存门槛高，普通开发者难以在消费级 GPU 上运行 70B+ 模型。

**核心亮点**
- 70B 模型跑在 4GB GPU；405B Llama 3.1 跑在 8GB；DeepSeek-V3(671B) 跑在 ~12GB
- v3.0 支持 FP8，新增 Qwen3-235B(3GB)、Qwen3、Llama 3.x/4、Phi-4、Gemma 等
- 统一 AutoModel 接口，免量化/蒸馏/剪枝

**github链接地址**：https://github.com/lyogavin/airllm
