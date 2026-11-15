# Is it Thinking or Cheating? Detecting Implicit Reward Hacking by Measuring Reasoning Effort

[返回方向导读](README.md)

- 会议/期刊：ICLR 2026
- 展示级别：Oral
- 类型：pure method
- [论文页面](https://iclr.cc/virtual/2026/poster/10010463)
- [在线PDF](https://arxiv.org/pdf/2510.01367)
- [本地PDF](<04_Is it Thinking or Cheating Detecting Implicit Reward Hacking by Measuring Reasoning E.pdf>)
- 代码：本次未核验到官方入口。

## 核心内容与阅读价值

TRACE逐步截断思维链，再让模型回答，用奖励随截断长度变化的曲线识别隐性奖励投机；把任务应有难度与模型实际投入联系起来。

## 问题与研究连接

推断：短推理也可能代表真正熟练，需检验正常高能力解法的误报；难度指标必须区分投机捷径和合法效率提升。

## 4–6 张 3090 的复现判断

低至中：检测阶段不训练，但多截断点、多次补全会放大推理成本；3090可并行评测开放小模型。

## 核验记录

核验日期为 2026-11-13。

https://iclr.cc/virtual/2026/oral/10010464

PDF 状态：已下载（26页）。
