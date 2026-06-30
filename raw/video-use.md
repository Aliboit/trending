### video-use — AI Agent 驱动的视频自动剪辑工具

**一句话总结**：video-use 让用户把原始素材交给 Claude Code 等编码 Agent，自动完成去口癖、删空白、调色、字幕和成片质检等全套后期工序。

**解决什么问题**：视频剪辑中大量重复手工操作（去除 filler words、删除停顿、加字幕、调色质检）耗时耗力，该项目将这些工序转化为可由 Agent 执行的自动化流水线。

**核心亮点**
- 自动剪掉 filler words 和无效片段，并在切点加入短音频淡化避免爆音。
- 支持自动调色、样式化字幕和自定义 ffmpeg 处理链路。
- 可并行生成动画叠加层，并在展示前自动评估渲染结果与切点质量。

**github链接地址**：https://github.com/browser-use/video-use
