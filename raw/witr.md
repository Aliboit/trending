### witr — 追踪任意进程/端口/容器/文件启动链路的 CLI+TUI 工具

**一句话总结**：回答「Why is this running?」——一条命令追踪任意进程、端口、容器或文件的完整启动链路。

**解决什么问题**：系统中运行的进程/服务/端口监听往往由多层间接调用（supervisor、容器、systemd、shell）触发，传统工具（ps、lsof、ss）无法回溯完整因果链。

**核心亮点**
- 支持 CLI、机器可读 JSON 和交互式 TUI 三种输出模式
- 提供浏览器沙箱环境，无需安装即可体验模拟 Linux 调查教程
- 跨平台支持，机器可读输出便于集成到运维自动化流程

**github链接地址**：https://github.com/pranshuparmar/witr
