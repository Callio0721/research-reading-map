# Thinkless: LLM Learns When to Think

[返回方向导读](README.md)

- 会议/期刊：NeurIPS 2025
- 展示级别：Poster
- 类型：pure method
- [论文页面](https://neurips.cc/virtual/2025/poster/117232)
- [在线PDF](https://proceedings.nips.cc/paper_files/paper/2025/file/de2ad3ed44ee4e675b3be42aa0b615d0-Paper-Conference.pdf)
- [本地PDF](<03_Thinkless LLM Learns When to Think.pdf>)
- [作者代码/项目入口](https://github.com/VainF/Thinkless)

## 核心内容与阅读价值

用控制token选择短答或长推理，DeGRPO分离模式选择与回答优化；难度不是固定标签，而取决于当前模型能力。

## 问题与研究连接

推断：分布外难题是否被误判为可短答，效率奖励是否牺牲少量困难样本，需要分难度曲线验证。

## 4–6 张 3090 的复现判断

中：推理评测容易；完整RL需多rollout及模型副本，建议先1.5—3B、小批次，再评估7B适配；并非免训练方法。

## 核验记录

核验日期为 2026-11-13。

https://neurips.cc/virtual/2025/poster/117232

PDF 状态：已下载（28页）。
