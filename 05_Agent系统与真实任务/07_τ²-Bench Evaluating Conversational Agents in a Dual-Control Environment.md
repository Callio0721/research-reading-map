# τ²-Bench: Evaluating Conversational Agents in a Dual-Control Environment

[返回方向导读](README.md)

- 会议/期刊：ICML 2026
- 展示级别：Oral（作者公开报告确认；出版由PMLR确认）
- 类型：pure benchmark
- [论文页面](https://proceedings.mlr.press/v306/barres26a.html)
- [在线PDF](https://arxiv.org/pdf/2506.07982)
- [本地PDF](<07_τ²-Bench Evaluating Conversational Agents in a Dual-Control Environment.pdf>)
- [作者代码/项目入口](https://github.com/sierra-research/tau2-bench)

## 核心内容与阅读价值

用户与Agent都拥有改变环境的工具；通过原子任务组合控制复杂度，并用环境状态验证结果。可分离推理错误与沟通协调错误，非常贴合hardness。

## 问题与研究连接

难度不只是问题长度，也包含依赖步骤、用户行动和信息分散。研究时需要固定用户模拟器及版本，区分任务变难与模拟器不可靠。

## 4–6 张 3090 的复现判断

评测免训练；小模型本地服务或API即可，主要是多轮交互采样。4—6张3090适合难度分层重复实验（推断）。

## 核验记录

核验日期为 2026-11-13。

PMLR https://proceedings.mlr.press/v306/barres26a.html 确认2026；Oral证据 https://victorbarres.github.io/assets/html/tau2-bench-icml2026-oral.html 。arXiv首发2025，按会议年归档。

PDF 状态：已下载（47页）。
