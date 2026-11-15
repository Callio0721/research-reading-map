# Difficulty Is Not Enough: Curriculum Learning for LLMs Fine-tuning Must Consider Utility

[返回方向导读](README.md)

- 会议/期刊：AAAI 2026
- 展示级别：Oral（作者官方仓库标注；会务级别未独立复核）
- 类型：pure method
- [论文页面](https://ojs.aaai.org/index.php/AAAI/article/view/40400)
- [在线PDF](https://raw.githubusercontent.com/Jiangzs1028/DUCL/178e10d44b60f714fcb5beff0af0c6a4353d74c4/paper/paper.pdf)
- [本地PDF](<04_Difficulty Is Not Enough Curriculum Learning for LLMs Fine-tuning Must Consider Utili.pdf>)
- [作者代码/项目入口](https://github.com/Jiangzs1028/DUCL)

## 核心内容与阅读价值

DUCL将样本难度与对模型提升的效用联合评分，再通过Window Ordering安排课程。它直接说明只按easy-to-hard排序不足以决定数据价值。

## 问题与研究连接

可研究问题（推断）：难度和效用在多模态数据中是否解耦，静态评分能否跟上训练期间模型能力变化。

## 4–6 张 3090 的复现判断

推断：4–6张3090适合小模型课程对照、7B级LoRA/QLoRA试验；论文完整训练配置仍需核实。评分代码已公开，不等于所有训练结果均能一键复现。

## 核验记录

核验日期为 2026-11-13。

https://github.com/Jiangzs1028/DUCL

PDF 状态：已下载（9页）。
