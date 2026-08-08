### mise — dev tools 版本管理、环境变量与任务运行器一体化 CLI

**一句话总结**：一个 CLI 集成 dev tools 版本管理、环境变量与任务运行器，让开发环境"开箱即一致"。

**解决什么问题**：新 shell、新 checkout、CI 任务间开发环境不一致是经典痛点；mise 在每条命令执行前准备好对应工具版本、环境变量与任务，全部收口到一个 mise.toml 文件。

**核心亮点**
- 安装与切换 node、python、cmake、terraform 等数百种开发工具
- 按项目目录加载环境变量（含 .env 等多种来源），告别手动 export
- 内置任务定义与运行器，一个 toml 文件统一工具、环境与任务配置

**github链接地址**：https://github.com/jdx/mise
