# 自适应推理与计算分配

[返回总览](../00_研究方向总览.md)

## 前沿与问题

从所有题统一多想、多采样，转向按样本选择思考长度、候选数、验证与搜索预算。

推理前很难知道题目真正需要多少计算；估计难度本身也花计算。额外计算可能放大错误，需要同时报告成功率、总token、延迟和失败分布。

## 阅读顺序

先读compute-optimal test-time scaling，再读自适应方法。只看accuracy会掩盖预算不同，先对齐总预算。

说明：方向判断是基于下列论文的综合推断；每篇方法说明以其链接为依据。资源建议未经本机实测，具体模型、上下文和训练配置会改变门槛。

| # | 论文 | 会议/期刊 | 展示级别 | PDF |
|---|---|---|---|---|
| 1 | [Reasoning with Sampling: Your Base Model is Smarter Than You Think](<01_Reasoning with Sampling Your Base Model is Smarter Than You Think.md>) | ICLR 2026 | Oral | [本地PDF](<01_Reasoning with Sampling Your Base Model is Smarter Than You Think.pdf>) |
| 2 | [Scaling LLM Test-Time Compute Optimally Can be More Effective than Scaling Parameters for Reasoning](<02_Scaling LLM Test-Time Compute Optimally Can be More Effective than Scaling Parameters.md>) | ICLR 2025 | Poster | [本地PDF](<02_Scaling LLM Test-Time Compute Optimally Can be More Effective than Scaling Parameters.pdf>) |
| 3 | [Thinkless: LLM Learns When to Think](<03_Thinkless LLM Learns When to Think.md>) | NeurIPS 2025 | Poster | [本地PDF](<03_Thinkless LLM Learns When to Think.pdf>) |
| 4 | [Think or Not? Selective Reasoning via Reinforcement Learning for Vision-Language Models](<04_Think or Not Selective Reasoning via Reinforcement Learning for Vision-Language Model.md>) | NeurIPS 2025 | Poster | [本地PDF](<04_Think or Not Selective Reasoning via Reinforcement Learning for Vision-Language Model.pdf>) |
| 5 | [On Test-Time Scaling for Vision-Language Models](<05_On Test-Time Scaling for Vision-Language Models.md>) | ECCV 2026 | Spotlight（作者报告确认） | [本地PDF](<05_On Test-Time Scaling for Vision-Language Models.pdf>) |
| 6 | [ReProbe: Efficient Test-Time Scaling of Multi-Step Reasoning by Probing Internal States of Large Language Models](<06_ReProbe Efficient Test-Time Scaling of Multi-Step Reasoning by Probing Internal State.md>) | ACL 2026 | Oral（第一作者主页确认） | [本地PDF](<06_ReProbe Efficient Test-Time Scaling of Multi-Step Reasoning by Probing Internal State.pdf>) |
| 7 | [Plan and Budget: Effective and Efficient Test-Time Scaling on Reasoning Large Language Models](<07_Plan and Budget Effective and Efficient Test-Time Scaling on Reasoning Large Language.md>) | ICLR 2026 | 主会录用（展示级别未核验） | [本地PDF](<07_Plan and Budget Effective and Efficient Test-Time Scaling on Reasoning Large Language.pdf>) |
