### vphone-cli — 虚拟 iPhone 命令行启动器

**一句话总结**：基于 Apple Virtualization.framework 与 PCC 研究 VM 基础设施启动虚拟 iPhone 的命令行工具。

**解决什么问题**：在 Apple Silicon 上以命令行方式引导虚拟 iPhone，供研究用途使用，无需依赖额外的虚拟化环境。

**核心亮点**
- 复用 Apple 的 PCC 研究 VM 基础设施，通过 Virtualization.framework 引导虚拟 iPhone
- 需 macOS 15+（Sequoia）Apple Silicon，并放宽 SIP/AMFI 以支持私有 PV=3 权限
- 提供 brew 一键安装与脚本化构建、签名、交叉编译 guest daemon

**github链接地址**：https://github.com/Lakr233/vphone-cli
