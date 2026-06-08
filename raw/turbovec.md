### turbovec — 基于 TurboQuant 的高性能 Rust 向量索引

**一句话总结**：基于 Google Research TurboQuant 的 Rust 向量索引，比 FAISS 更省内存还更快。

**解决什么问题**：千万级向量库用 float32 占用 31GB 内存、构建/调优复杂，FAISS 在 ARM 等架构上性能受限。

**核心亮点**
- 1000 万文档语料从 31GB 压到 4GB 内存，仍快于 FAISS 12–20%（ARM NEON / AVX-512 手写内核）
- 在线增量摄取，无需 train 步骤、无参数调优、无重建
- 支持搜索时按 id 白名单过滤（SIMD 内核级），完美适配带权限/租户的 RAG 场景

**github链接地址**：https://github.com/RyanCodrai/turbovec
