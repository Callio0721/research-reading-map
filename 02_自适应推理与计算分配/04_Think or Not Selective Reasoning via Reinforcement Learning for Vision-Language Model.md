# Think or Not? Selective Reasoning via Reinforcement Learning for Vision-Language Models

[返回方向导读](README.md)

- 会议/期刊：NeurIPS 2025
- 展示级别：Poster
- 类型：pure method
- [论文页面](https://neurips.cc/virtual/2025/poster/115882)
- [在线PDF](https://arxiv.org/pdf/2505.16854)
- [本地PDF](<04_Think or Not Selective Reasoning via Reinforcement Learning for Vision-Language Model.pdf>)
- [作者代码/项目入口](https://github.com/kokolerk/TON)

## 核心内容与阅读价值

TON先用thought dropout进行SFT，再用GRPO学会何时省略推理；覆盖语言、视觉和Agent任务，是多模态×hardness×效率的直接交叉阅读。

## 问题与研究连接

推断：视觉识别错误与逻辑推理不足可能需要不同预算；仅根据题目总难度选择思考模式可能掩盖这一区别。

## 4–6 张 3090 的复现判断

中：论文含3B/7B；4—6张3090优先3B缩小版SFT/RL，限制图像分辨率、长度和rollout；全配置未实测。

## 核验记录

核验日期为 2026-11-13。

https://neurips.cc/virtual/2025/poster/115882

PDF 状态：已下载（32页）。
