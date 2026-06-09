# Andyyyy64/whichllm

**一句话总结**：一行命令检测你的 GPU/CPU/RAM，从 HuggingFace 上推荐真实能跑且性能最强的本地 LLM。

**解决什么问题**：本地部署 LLM 时，参数量并不等于实际可用性，用户难以快速判断哪个量化版本在自己硬件上"既跑得动又跑得好"。

**核心亮点**：
- 排序基于实测的、考虑时效性的 benchmark 分数，而非参数量
- 支持 `--gpu "RTX 4090"` 模拟未购买硬件场景，辅助升级决策
- 提供 `upgrade`/`plan`/`run`/`snippet` 等子命令，覆盖选型→运行→脚本嵌入全链路

**GitHub 链接**：https://github.com/Andyyyy64/whichllm
