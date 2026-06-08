### llama.cpp — 极致优化的本地 LLM 推理引擎

**一句话总结**：用纯 C/C++ 极致优化的本地 LLM 推理引擎，几乎可在一切硬件上跑大模型。

**解决什么问题**：LLM 部署对硬件依赖重、依赖链复杂，难以在端侧/边缘设备/无 GPU 环境上以低成本运行。

**核心亮点**
- 零依赖 C/C++ 实现，覆盖 Apple Silicon/x86 AVX/AVX-512/AMX/RISC-V/CUDA/HIP/MUSA/Vulkan/SYCL
- 1.5~8 bit 整数量化，CPU+GPU 混合推理可跑超 VRAM 容量的模型
- 已成为 ggml 生态主战场，原生支持 gpt-oss MXFP4、多模态、WebGPU 浏览器内推理

**github链接地址**：https://github.com/ggml-org/llama.cpp
