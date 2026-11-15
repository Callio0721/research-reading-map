# AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials

[返回方向导读](README.md)

- 会议/期刊：ICLR 2025
- 展示级别：Spotlight（作者官方仓库确认；会务页面受限）
- 类型：method + benchmark
- [论文页面](https://arxiv.org/abs/2412.09605)
- [在线PDF](https://arxiv.org/pdf/2412.09605)
- [本地PDF](<04_AgentTrek Agent Trajectory Synthesis via Guiding Replay with Web Tutorials.pdf>)
- [作者代码/项目入口](https://github.com/xlang-ai/AgentTrek)

## 核心内容与阅读价值

从公开网页教程提炼任务步骤，借助视觉语言Agent回放并用评估器筛选，生成文本及截图动作轨迹用于GUI模型训练。

## 问题与研究连接

研究延伸：教程引导可能掩盖真实自主规划难度；按步骤数、视觉歧义、错误恢复区分数据难度，检查训练到开放环境的迁移。

## 4–6 张 3090 的复现判断

训练型且有数据合成成本；使用已发布数据做小规模LoRA较适合3090集群（推断），从头抓取和回放整套数据耗时较大。

## 核验记录

核验日期为 2026-11-13。

https://github.com/xlang-ai/AgentTrek 标题标注ICLR2025 Spotlight；论文首页确认会议。

PDF 状态：已下载（22页）。
