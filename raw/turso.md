### turso — Rust 编写、兼容 SQLite 的进程内 SQL 数据库

**一句话总结**：Turso 是一个用 Rust 编写、兼容 SQLite 的进程内 SQL 数据库。

**解决什么问题**：它面向需要 SQLite 兼容性但希望获得更强并发、变更捕获、多语言和异步 I/O 能力的应用场景。

**核心亮点**
- 兼容 SQLite SQL 方言、文件格式和 C API，降低迁移成本。
- 支持 BEGIN CONCURRENT、MVCC 和 CDC，增强写入吞吐与实时数据变更追踪。
- 覆盖 Go、JavaScript、Java、.NET、Python、Rust、WASM 等多语言环境。

**github链接地址**：https://github.com/tursodatabase/turso
