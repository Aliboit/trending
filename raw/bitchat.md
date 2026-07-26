### bitchat — 去中心化蓝牙 Mesh + Nostr 双通道聊天，无账号无服务器

**一句话总结**：去中心化点对点聊天应用，采用蓝牙 Mesh（离线）+ Nostr（联网）双通道架构，无账号、无手机号、无中心服务器。

**解决什么问题**：传统即时通讯依赖中心服务器与账号体系，存在隐私与可用性风险；bitchat 用蓝牙本地 Mesh 实现离线通信，Nostr 实现全球可达，智能路由自动切换。

**核心亮点**
- 双通道架构：蓝牙 Mesh 离线 + Nostr 联网，自动择优
- 零身份要求：无账号、无手机号、无中心服务器
- 基于位置频道：用 geohash 坐标在 Nostr 上构建地理聊天室

**github链接地址**：https://github.com/permissionlesstech/bitchat
