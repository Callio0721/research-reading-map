# 训练课程与强化学习

[返回总览](../00_研究方向总览.md)

## 前沿与问题

从固定数据与统一训练配方，转向按能力边界、样本效用和可验证反馈动态组织训练。

太难的数据可能几乎没有正奖励，太简单的数据缺少学习信号；当前成功率不等于长期迁移收益，自动生成任务还可能钻验证器漏洞。

## 阅读顺序

先读DUCL建立难度与效用的区别，再读Absolute Zero及课程/RL论文；保留训练方法作为主线，不局限免训练。

说明：方向判断是基于下列论文的综合推断；每篇方法说明以其链接为依据。资源建议未经本机实测，具体模型、上下文和训练配置会改变门槛。

| # | 论文 | 会议/期刊 | 展示级别 | PDF |
|---|---|---|---|---|
| 1 | [LILO: Learning to Reason at the Frontier of Learnability](<01_LILO Learning to Reason at the Frontier of Learnability.md>) | NeurIPS 2025 | Poster | [本地PDF](<01_LILO Learning to Reason at the Frontier of Learnability.pdf>) |
| 2 | [Absolute Zero: Reinforced Self-play Reasoning with Zero Data](<02_Absolute Zero Reinforced Self-play Reasoning with Zero Data.md>) | NeurIPS 2025 | Spotlight | [本地PDF](<02_Absolute Zero Reinforced Self-play Reasoning with Zero Data.pdf>) |
| 3 | [The Coverage Principle: How Pre-Training Enables Post-Training](<03_The Coverage Principle How Pre-Training Enables Post-Training.md>) | ICLR 2026 | Oral | [本地PDF](<03_The Coverage Principle How Pre-Training Enables Post-Training.pdf>) |
| 4 | [Difficulty Is Not Enough: Curriculum Learning for LLMs Fine-tuning Must Consider Utility](<04_Difficulty Is Not Enough Curriculum Learning for LLMs Fine-tuning Must Consider Utili.md>) | AAAI 2026 | Oral（作者官方仓库标注；会务级别未独立复核） | [本地PDF](<04_Difficulty Is Not Enough Curriculum Learning for LLMs Fine-tuning Must Consider Utili.pdf>) |
| 5 | [RuCL: Stratified Rubric-Based Curriculum Learning for Multimodal Large Language Model Reasoning](<05_RuCL Stratified Rubric-Based Curriculum Learning for Multimodal Large Language Model.md>) | ICML 2026 | 主会录用（展示级别未核验） | [本地PDF](<05_RuCL Stratified Rubric-Based Curriculum Learning for Multimodal Large Language Model.pdf>) |
