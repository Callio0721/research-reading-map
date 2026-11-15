# NarrativeTrack: Evaluating Entity-Centric Reasoning for Narrative Understanding

[返回方向导读](README.md)

- 会议/期刊：ECCV 2026
- 展示级别：Spotlight（作者主页确认；会务页面访问失败）
- 类型：pure benchmark
- [论文页面](https://arxiv.org/abs/2601.01095)
- [在线PDF](https://arxiv.org/pdf/2601.01095)
- [本地PDF](<06_NarrativeTrack Evaluating Entity-Centric Reasoning for Narrative Understanding.pdf>)
- [作者代码/项目入口](https://github.com/apple-aiml-research/ml-narrativetrack)

## 核心内容与阅读价值

以实体存在、实体变化、实体歧义构成递进的视频理解评测，把叙事难度拆成可解释维度。与笼统的长视频准确率相比，更适合研究困难来自哪里。

## 问题与研究连接

研究问题（推断）：三层分类是否在不同模型上保持难度单调性？如何分离遮挡、身份混淆、时间跨度的影响？作者仓库提示自动生成QA需人工复核。

## 4–6 张 3090 的复现判断

推断：评测已发布题目无需训练，4–6张3090可按模型/样本分卡运行；重新构建完整数据管线涉及检测、跟踪、API标注及人工验证。

## 核验记录

核验日期为 2026-11-13。

https://hyeonjeongha.github.io/publications/

PDF 状态：已下载（29页）。
