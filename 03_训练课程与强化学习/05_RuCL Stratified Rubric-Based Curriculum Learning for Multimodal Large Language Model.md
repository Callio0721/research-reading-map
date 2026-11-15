# RuCL: Stratified Rubric-Based Curriculum Learning for Multimodal Large Language Model Reasoning

[返回方向导读](README.md)

- 会议/期刊：ICML 2026
- 展示级别：主会录用（展示级别未核验）
- 类型：pure method
- [论文页面](https://proceedings.mlr.press/v306/chen26bk.html)
- [在线PDF](https://raw.githubusercontent.com/mlresearch/v306/main/assets/chen26bk/chen26bk.pdf)
- [本地PDF](<05_RuCL Stratified Rubric-Based Curriculum Learning for Multimodal Large Language Model.pdf>)
- 代码：本次未核验到官方入口。

## 核心内容与阅读价值

将课程应用于奖励设计，按模型能力分层组织可复用的评分准则，动态提高更难的逻辑推理准则的权重。可与 DUCL 的样本排序、LILO 的边界题采样做对照。

## 问题与研究连接

可检验奖励准则的难度顺序能否跨模型迁移。视觉证据不足和推理步骤不合格需要分别评估，也应计入评分模型开销。

## 4–6 张 3090 的复现判断

论文在 Qwen2.5-VL-7B 上评估。建议用 4–6 张 3090 先复现固定与动态准则权重的缩小版对照，控制图像分辨率、采样数和序列长度。

## 核验记录

核验日期为 2026-11-13。

[PMLR 正式论文页](https://proceedings.mlr.press/v306/chen26bk.html)确认 ICML 2026 及方法。

PDF 状态：已下载（31页）。
