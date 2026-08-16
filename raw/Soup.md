### Soup — YAML 微调 LLM 工具

**一句话总结**：一个 YAML 配置 + 一条命令完成 LLM 微调，4GB 笔记本 GPU 就能训 8B 模型。

**解决什么问题**：消除微调 LLM 时的 SSH 折腾和配置地狱，`soup init --template chat && soup train` 即可开训。

**核心亮点**
- 层流（Layer streaming）技术把冻结的基座模型挡在显存外，逐层喂给 GPU
- RTX 3050 4GB 上实测 Llama-3.1-8B + NF4 达 119.6 tok/s、峰值 3.32GB，且与常驻运行 bit-exact
- 结果在 H100 上独立复现（113 tok/s，同样 3.32GB），可信度高

**github链接地址**：https://github.com/MakazhanAlpamys/Soup
