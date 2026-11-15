# MathGAP: Out-of-Distribution Evaluation on Problems with Arbitrarily Complex Proofs

[返回方向导读](README.md)

- 会议/期刊：ICLR 2025
- 展示级别：Poster
- 类型：pure benchmark
- [论文页面](https://iclr.cc/virtual/2025/poster/30934)
- [在线PDF](https://proceedings.iclr.cc/paper_files/paper/2025/file/f9c2ab8d429044e0c35bcece2ff6d123-Paper-Conference.pdf)
- [本地PDF](<01_MathGAP Out-of-Distribution Evaluation on Problems with Arbitrarily Complex Proofs.pdf>)
- [作者代码/项目入口](https://github.com/eth-lre/mathgap-experiments)

## 核心内容与阅读价值

按证明树深度、宽度和结构生成算术题及推理链，直接研究从易到难的泛化；适合建立可控制的hardness坐标，而不只依据模型答错率给题分档。

## 问题与研究连接

推断：结构难度、表述顺序和模型熟悉度可能混杂；可检验相同证明图在文本/图像表示下的难度差异。

## 4–6 张 3090 的复现判断

低：无需训练，CPU生成题目，1张3090推理小模型，其余卡并行采样；完整跨模型评测成本随样本数增长。

## 核验记录

核验日期为 2026-11-13。

https://iclr.cc/virtual/2025/poster/30934

PDF 状态：已下载（23页）。
