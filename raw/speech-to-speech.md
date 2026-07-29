### speech-to-speech — 低延迟全模块化语音 Agent 管道

**一句话总结**：低延迟、全模块化的语音 Agent 管道（VAD→STT→LLM→TTS），兼容 OpenAI Realtime WebSocket API。

**解决什么问题**：为开发者提供一个可完全本地运行、每个组件可替换的语音对话 Agent 框架，降低构建语音应用的门槛。

**核心亮点**
- 完整管道 VAD→STT→LLM→TTS，每个环节可自由替换为开源或商业模型
- LLM 槽位兼容 OpenAI 协议，可对接托管服务或本地 vLLM/llama.cpp
- 已在生产环境中为数千台 Reachy Mini 机器人提供对话后端

**github链接地址**：https://github.com/huggingface/speech-to-speech
