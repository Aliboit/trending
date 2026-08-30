### tailcat — 像 netcat 但走 Tailscale 数据平面的点对点隧道工具

**一句话总结**：Tailcat 是 Tailscale 开源组件的「重混」，像 netcat 一样工作，但走 Tailscale 数据平面、无需 Tailscale 控制平面。

**解决什么问题**：让你在两台机器之间快速建立点对点 WireGuard 加密隧道，连接元数据完全带外交换，摆脱对 Tailscale 控制平面的依赖。

**核心亮点**
- 复用 magicsock 数据平面，点到点 WireGuard 加密，DERP 做 NAT 打洞与兜底中继
- 连接元数据带外自定义交换，想怎么传就怎么传
- CLI（cmd/tailcat）与可导入的 Go 库（github.com/tailscale/tailcat）双形态提供

**github链接地址**：https://github.com/tailscale/tailcat
