# Reasoning with Sampling: Your Base Model is Smarter Than You Think

[返回方向导读](README.md)

- 会议/期刊：ICLR 2026
- 展示级别：Oral
- 类型：pure method
- [论文页面](https://iclr.cc/virtual/2026/poster/10009093)
- [在线PDF](https://arxiv.org/pdf/2510.14901)
- [本地PDF](<01_Reasoning with Sampling Your Base Model is Smarter Than You Think.pdf>)
- [作者代码/项目入口](https://github.com/aakaran/training-free-reasoning)

## 核心内容与阅读价值

利用基础模型自身似然进行MCMC式迭代采样，无需额外训练、数据或验证器；适合先研究不同难度下采样预算与解题能力的关系。

## 问题与研究连接

推断：免训练仍可能需要多次生成和重评分；需同时报告延迟、总token、通过率和难度分层收益。

## 4–6 张 3090 的复现判断

低至中：优先3—7B及短上下文；4—6张3090可并行跑种子和预算档，完整大模型对比成本更高。

## 核验记录

核验日期为 2026-11-13。

https://iclr.cc/virtual/2026/oral/10009094

PDF 状态：已下载（20页）。
