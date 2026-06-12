### container — Apple 原生 Mac Linux 容器运行时

**一句话总结**：Apple 官方推出的、基于轻量虚拟机在 Mac 上运行 Linux 容器的原生工具。

**解决什么问题**：解决 Mac 开发者运行 Linux 容器时依赖 Docker Desktop 等第三方工具、性能开销大、与 Apple Silicon 集成不够紧密的问题。

**核心亮点**
- 用 Swift 编写，针对 Apple Silicon 深度优化，每个容器一个轻量虚拟机
- 完全兼容 OCI 镜像标准，可与任何标准容器仓库互通
- 底层基于 Containerization Swift 包，利用 macOS 26 的虚拟化和网络新特性

**github链接地址**：https://github.com/apple/container
