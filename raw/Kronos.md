### 8. Kronos — 金融市场 K 线基础模型

**一句话总结**：首个金融 K 线开源基础模型，将 OHLCV 数据量化为离散 Token 后用自回归 Transformer 预训练，已被 AAAI 2026 收录。

**解决什么问题**：通用时序模型无法捕捉金融数据的高噪声特性——Kronos 专为 K 线序列设计，支持预测、分类等多种量化任务。

**核心亮点**
- 两阶段框架：专用 Tokenizer 量化多维 K 线 → 大型自回归 Transformer 预训练
- 基于 45+ 全球交易所数据训练，模型族从 4.1M（mini）到 499M（large）参数
- 提供 KronosPredictor 类，几行代码即可从原始数据到预测结果，含 BTC/USDT 24h 预测 Live Demo

---