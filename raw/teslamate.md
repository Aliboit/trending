### teslamate — 自托管 Tesla 车辆数据记录器与可视化仪表盘

**一句话总结**：自托管的 Tesla 车辆数据记录器，用 Grafana 把你的特斯拉变成可视化仪表盘。

**解决什么问题**：官方 App 不保留长期里程、能耗、充电、行程数据，TeslaMate 把这些都落到本地 Postgres 里供随意分析。

**核心亮点**
- Elixir 编写，数据存 Postgres，Grafana 出图
- 车辆数据同步发布到本地 MQTT，便于二次开发与 Home Assistant 集成
- 官方明确警告只用官方源，警惕仿冒站和恶意 App

**github链接地址**：https://github.com/teslamate-org/teslamate
