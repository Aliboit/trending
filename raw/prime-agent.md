### prime-agent — 自我进化的 RLM 编码与长时自主任务智能体

**一句话总结**：一个围绕"递归语言模型（RLM）"和"持续化 Harness"两大抽象构建的开源编码与研究智能体，擅长长时自主工作。

**解决什么问题**：传统 AI 编码助手缺乏持久上下文与自我改进能力，难以胜任需要长期记忆、技能积累和子智能体协作的复杂研发任务；Prime Agent 通过持久化 Python 控制环境与可精炼的 harness 状态来解决这一瓶颈。

**核心亮点**
- 引入 Recursive Language Model，把上下文当作变量、把工具当作递归子智能体函数调用，运行在持久 REPL 中
- Continual Harness 将补充提示、记忆、技能描述、可复用子智能体规格作为可持久状态，支持基于证据的局部增量更新
- 开源、面向通用编码与长周期研究任务，定位为可自我进化的 agent

**github链接地址**：https://github.com/PrimeIntellect-ai/prime-agent
