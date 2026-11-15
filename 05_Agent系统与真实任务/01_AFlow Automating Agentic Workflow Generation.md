# AFlow: Automating Agentic Workflow Generation

[返回方向导读](README.md)

- 会议/期刊：ICLR 2025
- 展示级别：Oral（作者官方仓库确认；会务页面受限）
- 类型：pure method
- [论文页面](https://arxiv.org/abs/2410.10762)
- [在线PDF](https://arxiv.org/pdf/2410.10762)
- [本地PDF](<01_AFlow Automating Agentic Workflow Generation.pdf>)
- [作者代码/项目入口](https://github.com/FoundationAgents/AFlow)

## 核心内容与阅读价值

把工作流表示为可修改代码，用蒙特卡洛树搜索和执行反馈搜索模型调用结构；适合研究任务难度变化时，什么工作流值得增加验证或分支。

## 问题与研究连接

研究延伸：按难度分层比较搜索收益，并控制搜索阶段与部署阶段总调用成本，避免把更多采样误判为结构优势。

## 4–6 张 3090 的复现判断

免权重训练；本地小模型或API均可，主要成本是搜索调用次数。4—6张3090可做多任务并行推理（可行性推断，未实测）。

## 核验记录

核验日期为 2026-11-13。

论文首页确认ICLR 2025；https://github.com/FoundationAgents/AFlow 明确标注Oral。

PDF 状态：已下载（38页）。
