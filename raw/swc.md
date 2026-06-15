### swc — Rust 编写的超高速 TS/JS 编译器

**一句话总结**：用 Rust 写的 TypeScript / JavaScript 编译器，被 Next.js、Deno 等大项目采用。

**解决什么问题**：替代 Babel/tsc 等基于 JS 的编译链路，大幅缩短前端构建和转译时间。

**核心亮点**
- 同一份代码同时作为 Rust 库和 JS 库提供，覆盖 Node 和 Rust 两端用户
- MSRV 1.73，提供官方一键升级所有 swc crate 的脚本
- 已在 Vercel/Next.js 等生产环境大规模验证

**github链接地址**：https://github.com/swc-project/swc
