# In-the-Flow Agentic System Optimization for Effective Planning and Tool Use

[返回方向导读](README.md)

- 会议/期刊：ICLR 2026
- 展示级别：Oral（作者项目页及arXiv确认；会务页面受限）
- 类型：pure method
- [论文页面](https://arxiv.org/abs/2510.05592)
- [在线PDF](https://arxiv.org/pdf/2510.05592)
- [本地PDF](<03_In-the-Flow Agentic System Optimization for Effective Planning and Tool Use.pdf>)
- [作者代码/项目入口](https://github.com/lupantech/AgentFlow)

## 核心内容与阅读价值

AgentFlow将规划、执行、验证、生成四模块通过动态记忆连接，在真实多轮调用中训练规划器。Flow-GRPO用轨迹级反馈优化各轮决策。

## 问题与研究连接

长程稀疏奖励的信用分配仍是关键；可研究难度分层后模块收益、错误传播及最终奖励广播的局限（研究推断）。

## 4–6 张 3090 的复现判断

论文研究3B/7B；推理可先复现。完整在线RL含多轮rollout和多个工具模型，4—6张3090仅建议先验证缩小版或LoRA，不能承诺原配置可跑。

## 核验记录

核验日期为 2026-11-13。

https://agentflow.stanford.edu/ 明确ICLR 2026 Oral；已读方法概览与结果说明。

PDF 状态：已下载（47页）。
