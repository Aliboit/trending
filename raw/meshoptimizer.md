### meshoptimizer — 3D 网格优化库

**一句话总结**：3D 网格优化库，让模型更小、渲染更快，广泛用于游戏和实时渲染领域。

**解决什么问题**：GPU 渲染三角形网格时，顶点缓存、overdraw、顶点数据布局等会严重影响渲染性能。该库提供一系列算法优化这些环节，同时支持网格简化和压缩，在不损失视觉质量的前提下大幅提升渲染效率。

**核心亮点**
- 提供顶点缓存优化、overdraw 优化、顶点数据布局优化等全套算法
- 配套 gltfpack 命令行工具，可自动优化 glTF 文件
- 提供 C/C++ 接口，支持 Rust（meshopt crate）和 JavaScript（meshoptimizer.js）多语言绑定

**github链接地址**：https://github.com/zeux/meshoptimizer
