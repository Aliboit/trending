### stable-worldmodel — 可复现世界模型研究平台

**一句话总结**：可复现的世界模型研究平台，统一数据采集 → 训练 → 模型预测控制评估三阶段。

**解决什么问题**：世界模型研究分散在各种环境、格式和评估协议中，难以横向对比。stable-worldmodel 提供标准化接口 + 环境套件 + 基线 + 求解器，让研究者专注模型创新。

**核心亮点**
- 三阶段统一 API：`World.collect()` → 训练 → `WorldModelPolicy` + CEM 求解器评估
- 支持多种数据格式（Lance / HDF5 / NPZ / 视频 / LeRobot），自动检测
- 附带 LeWM 和 DINO-WM 的参考实现，可直接复现基线

**github链接地址**：https://github.com/galilai-group/stable-worldmodel
