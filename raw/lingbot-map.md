### LingBot-Map — 流式 3D 重建前馈基础模型

**一句话总结**：LingBot-Map 是一个用于流式 3D 重建的前馈式基础模型，面向长序列实时场景提供高效重建能力。

**解决什么问题**：长序列、实时场景中的 3D 重建常面临速度、漂移校正和几何一致性难题；LingBot-Map 通过 Geometric Context Transformer 统一坐标定位、密集几何线索与长程漂移校正，支持超过 10,000 帧的流式推理。

**核心亮点**
- 通过 Geometric Context Transformer 统一坐标定位、密集几何线索与长程漂移校正
- 使用 paged KV cache 注意力机制，支持超过 10,000 帧的长序列流式推理
- 在 518×378 分辨率下可达到约 20 FPS，强调实时性与重建质量

**github链接地址**：https://github.com/Robbyant/lingbot-map
