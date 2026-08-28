### go-modern-guidelines — 帮助 AI 编码 agent 写现代 Go 代码的指南

**一句话总结**：JetBrains 出品的指南库，帮助 AI 编码 agent 写出符合现代习惯的 Go 代码。

**解决什么问题**：训练数据滞后与频率偏差导致 agent 生成过时的 Go 写法；本指南补齐了模型不熟悉的现代特性。

**核心亮点**
- 覆盖 Go 1.0 至 1.27 最有用的特性，包括 Go 1.26 的 `new(42)` 与 `errors.AsType[T]`
- 引导 agent 从 go.mod 检测版本并选用现代惯用法（如 `slices.Contains`、`cmp.Or`、`max(a,b)`）
- 对齐 modernize 分析器所覆盖的现代化目标

**github链接地址**：https://github.com/JetBrains/go-modern-guidelines
