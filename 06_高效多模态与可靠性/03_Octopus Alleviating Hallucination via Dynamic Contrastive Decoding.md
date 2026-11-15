# Octopus: Alleviating Hallucination via Dynamic Contrastive Decoding

[返回方向导读](README.md)

- 会议/期刊：CVPR 2025
- 展示级别：Highlight
- 类型：pure method
- [论文页面](https://arxiv.org/abs/2503.00361)
- [在线PDF](https://arxiv.org/pdf/2503.00361)
- [本地PDF](<03_Octopus Alleviating Hallucination via Dynamic Contrastive Decoding.pdf>)
- [作者代码/项目入口](https://github.com/LijunZhang01/Octopus)

## 核心内容与阅读价值

识别不同生成步骤中的幻觉类型，再动态选择对比解码策略，避免所有样本使用同一种扰动。

## 问题与研究连接

并非完全免训练：论文训练控制模块而冻结基础LVLM；适合研究难例上路由是否校准、额外解码是否值得。

## 4–6 张 3090 的复现判断

中（推断）：冻结主模型降低训练负担，但控制器训练和多分支解码仍耗算力；可用已有权重先评测。

## 核验记录

核验日期为 2026-11-13。

https://cvpr.thecvf.com/Conferences/2025/AcceptedPapers

PDF 状态：已下载（11页）。
