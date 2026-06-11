### MasterDnsVPN — 基于 DNS 隧道的高级 VPN，专为审查绕过和恶劣网络优化

**一句话总结**：用 DNS 查询/响应承载 TCP 流量的高级 VPN，专为审查绕过和恶劣网络优化。

**解决什么问题**：现有 DNS 隧道（DNSTT、SlipStream）在高丢包、解析器多样性、传输头开销上仍有明显短板。

**核心亮点**
- 自研协议 + ARQ，相比 SlipStream（QUIC）和 DNSTT（KCP+Noise）传输头开销更低
- 解析器负载均衡，面向多种 resolver 行为做兼容
- 高丢包场景下保持稳定性和吞吐，Go 实现易部署

**github链接地址**：https://github.com/masterking32/MasterDnsVPN
