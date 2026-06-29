### CuPy — 兼容 NumPy/SciPy 的 GPU 加速计算库

**一句话总结**：CuPy 是一个兼容 NumPy/SciPy API 的 Python GPU 加速数组计算库，支持 NVIDIA CUDA 与 AMD ROCm 平台。

**解决什么问题**：科学计算与数据处理中的数组运算在 CPU 上可能性能不足，而重写 CUDA/ROCm 代码门槛较高；CuPy 提供接近 NumPy/SciPy 的数组接口，让大量现有代码能更平滑地迁移到 GPU。

**核心亮点**
- 提供接近 NumPy/SciPy 的数组接口，可作为 GPU 加速替代方案使用
- 支持 NVIDIA CUDA 与 AMD ROCm 双平台
- 除高层数组 API 外，也暴露 RawKernels、Streams、CUDA Runtime API 等底层能力

**github链接地址**：https://github.com/cupy/cupy
