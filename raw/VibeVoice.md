### VibeVoice — 微软开源前沿语音 AI

**一句话总结**：微软开源的前沿语音 AI 项目，涵盖语音识别（ASR）与语音合成，通过异构量化技术实现边缘 CPU 实时推理。

**解决什么问题**：高质量语音模型体积大、依赖 GPU 难以本地部署；VibeVoice 通过异构量化将模型从 4.62 GB 压缩至 1.58 GB，仅需 3+ CPU 线程即可实现实时推理（RTF < 1）。

**核心亮点**
- VibeVoice-ASR-BitNet 采用 I8_S + I2_S 异构量化，CPU 端实时推理不依赖 GPU
- 已集成至 Azure AI Foundry Labs 与 Hugging Face Transformers 生态
- 统一语音识别模型，开源且持续迭代（最新发布于 2026-07-23）

**github链接地址**：https://github.com/microsoft/VibeVoice
