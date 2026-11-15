# On Test-Time Scaling for Vision-Language Models

[返回方向导读](README.md)

- 会议/期刊：ECCV 2026
- 展示级别：Spotlight（作者报告确认）
- 类型：pure benchmark
- [论文页面](https://arxiv.org/abs/2606.28864)
- [在线PDF](https://arxiv.org/pdf/2606.28864v2)
- [本地PDF](<05_On Test-Time Scaling for Vision-Language Models.pdf>)
- 代码：本次未核验到官方入口。

## 核心内容与阅读价值

系统比较多种测试时推理方法在视觉语言模型中的表现。论文观察到加算力的效果因任务和模型而异，视觉信息主要在推理链早期被使用，过长的推理有时反而损害表现。

## 问题与研究连接

可检验的问题是，增加推理预算的收益能否由感知难度和逻辑难度分别预测。先控制图像分辨率与推理预算，再比较重看图像和延长文本推理。

## 4–6 张 3090 的复现判断

免训练评测。用较小模型复现少数预算档适合 3090，完整实验涵盖多模型、多基准与较大模型，宜作为后续扩展。

## 核验记录

核验日期为 2026-11-13。

[作者报告](https://www.linkedin.com/posts/fawaz-sammani-2ba4a7184_eccv2026-activity-7504517037025652737-Z5IM)确认 Spotlight。[论文版本记录](https://arxiv.org/abs/2606.28864)确认 ECCV 2026。

PDF 状态：已下载（35页）。
