# ReProbe: Efficient Test-Time Scaling of Multi-Step Reasoning by Probing Internal States of Large Language Models

[返回方向导读](README.md)

- 会议/期刊：ACL 2026
- 展示级别：Oral（第一作者主页确认）
- 类型：pure method
- [论文页面](https://aclanthology.org/2026.acl-long.536/)
- [在线PDF](https://aclanthology.org/2026.acl-long.536.pdf)
- [本地PDF](<06_ReProbe Efficient Test-Time Scaling of Multi-Step Reasoning by Probing Internal State.pdf>)
- 代码：本次未核验到官方入口。

## 核心内容与阅读价值

从冻结语言模型的内部状态预测推理步骤可信度，再用于候选步骤选择。它提供了与多采样和大过程奖励模型不同的轻量验证路线。

## 问题与研究连接

可检验步骤可信度在不同题型、模型和难度档是否保持校准。研究选分支的收益时需把提取内部状态及探针训练的开销计入。

## 4–6 张 3090 的复现判断

小规模实验适合单卡提取状态和训练轻量探针，多卡并行生成。需要模型内部状态和步骤标签，完整训练及跨域对比需另核。

## 核验记录

核验日期为 2026-11-13。

[ACL Anthology](https://aclanthology.org/2026.acl-long.536/)确认出版，[第一作者主页](https://edisonni-hku.github.io/)确认 Oral。

PDF 状态：已下载（23页）。
