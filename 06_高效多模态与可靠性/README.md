# 高效多模态与可靠性

[返回总览](../00_研究方向总览.md)

## 前沿与问题

从只压缩平均token数量，转向兼顾视觉证据、难例保真、置信度和分布变化；可靠性是决定何时加预算的重要信号。

压缩可保住平均分却损伤小字、计数、细粒度空间难题；一致性不保证正确，不确定性不等于任务难度。

## 阅读顺序

将高效方法当作hardness研究中的干预工具：测试哪些难度维度最先受损；UQLM可提供置信度对照。

说明：方向判断是基于下列论文的综合推断；每篇方法说明以其链接为依据。资源建议未经本机实测，具体模型、上下文和训练配置会改变门槛。

| # | 论文 | 会议/期刊 | 展示级别 | PDF |
|---|---|---|---|---|
| 1 | [Thinking with Drafts: Speculative Temporal Reasoning for Efficient Long Video Understanding](<01_Thinking with Drafts Speculative Temporal Reasoning for Efficient Long Video Understa.md>) | CVPR 2026 | Oral（Award candidate） | [本地PDF](<01_Thinking with Drafts Speculative Temporal Reasoning for Efficient Long Video Understa.pdf>) |
| 2 | [VisionZip: Longer is Better but Not Necessary in Vision Language Models](<02_VisionZip Longer is Better but Not Necessary in Vision Language Models.md>) | CVPR 2025 | 主会；未核实Oral/Highlight | [本地PDF](<02_VisionZip Longer is Better but Not Necessary in Vision Language Models.pdf>) |
| 3 | [Octopus: Alleviating Hallucination via Dynamic Contrastive Decoding](<03_Octopus Alleviating Hallucination via Dynamic Contrastive Decoding.md>) | CVPR 2025 | Highlight | [本地PDF](<03_Octopus Alleviating Hallucination via Dynamic Contrastive Decoding.pdf>) |
| 4 | [PhD: A ChatGPT-Prompted Visual Hallucination Evaluation Dataset](<04_PhD A ChatGPT-Prompted Visual Hallucination Evaluation Dataset.md>) | CVPR 2025 | Highlight | [本地PDF](<04_PhD A ChatGPT-Prompted Visual Hallucination Evaluation Dataset.pdf>) |
| 5 | [MASH-VLM: Mitigating Action-Scene Hallucination in Video-LLMs through Disentangled Spatial-Temporal Representations](<05_MASH-VLM Mitigating Action-Scene Hallucination in Video-LLMs through Disentangled Spa.md>) | CVPR 2025 | Highlight | [本地PDF](<05_MASH-VLM Mitigating Action-Scene Hallucination in Video-LLMs through Disentangled Spa.pdf>) |
| 6 | [ChartCap: Mitigating Hallucination of Dense Chart Captioning](<06_ChartCap Mitigating Hallucination of Dense Chart Captioning.md>) | ICCV 2025 | Highlight | [本地PDF](<06_ChartCap Mitigating Hallucination of Dense Chart Captioning.pdf>) |
| 7 | [UQLM: A Python Package for Uncertainty Quantification in Large Language Models](<07_UQLM A Python Package for Uncertainty Quantification in Large Language Models.md>) | JMLR 2026 | 期刊论文，无Oral/Highlight等级 | [本地PDF](<07_UQLM A Python Package for Uncertainty Quantification in Large Language Models.pdf>) |
| 8 | [Scaling Capability in Token Space: An Analysis of Large Vision Language Model](<08_Scaling Capability in Token Space An Analysis of Large Vision Language Model.md>) | JMLR 2025 | 期刊论文，无Oral/Highlight等级 | [本地PDF](<08_Scaling Capability in Token Space An Analysis of Large Vision Language Model.pdf>) |
