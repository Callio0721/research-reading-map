# Agent系统与真实任务

[返回总览](../00_研究方向总览.md)

## 前沿与问题

从单次回答转向多轮工具使用、记忆、工作流优化和可执行的真实任务评测；与你已有Harness Scaling、DeliveryBench阅读相接。

错误沿轨迹累积，用户模拟器、环境版本和工具权限会改变结果；“更复杂的系统”与“用了更多调用预算”经常混杂。

## 阅读顺序

先读τ²-Bench与AFlow/GEPA，再读AgentFlow和AgentTrek。用任务依赖深度、信息分散和恢复次数刻画Agent hardness。

说明：方向判断是基于下列论文的综合推断；每篇方法说明以其链接为依据。资源建议未经本机实测，具体模型、上下文和训练配置会改变门槛。

| # | 论文 | 会议/期刊 | 展示级别 | PDF |
|---|---|---|---|---|
| 1 | [AFlow: Automating Agentic Workflow Generation](<01_AFlow Automating Agentic Workflow Generation.md>) | ICLR 2025 | Oral（作者官方仓库确认；会务页面受限） | [本地PDF](<01_AFlow Automating Agentic Workflow Generation.pdf>) |
| 2 | [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](<02_GEPA Reflective Prompt Evolution Can Outperform Reinforcement Learning.md>) | ICLR 2026 | Oral（作者arXiv元数据确认；会务页面受限） | [本地PDF](<02_GEPA Reflective Prompt Evolution Can Outperform Reinforcement Learning.pdf>) |
| 3 | [In-the-Flow Agentic System Optimization for Effective Planning and Tool Use](<03_In-the-Flow Agentic System Optimization for Effective Planning and Tool Use.md>) | ICLR 2026 | Oral（作者项目页及arXiv确认；会务页面受限） | [本地PDF](<03_In-the-Flow Agentic System Optimization for Effective Planning and Tool Use.pdf>) |
| 4 | [AgentTrek: Agent Trajectory Synthesis via Guiding Replay with Web Tutorials](<04_AgentTrek Agent Trajectory Synthesis via Guiding Replay with Web Tutorials.md>) | ICLR 2025 | Spotlight（作者官方仓库确认；会务页面受限） | [本地PDF](<04_AgentTrek Agent Trajectory Synthesis via Guiding Replay with Web Tutorials.pdf>) |
| 5 | [A-Mem: Agentic Memory for LLM Agents](<05_A-Mem Agentic Memory for LLM Agents.md>) | NeurIPS 2025 | 主会录用；未核验Oral/Spotlight，不计入优选等级 | [本地PDF](<05_A-Mem Agentic Memory for LLM Agents.pdf>) |
| 6 | [AstaBench: Rigorous Benchmarking of AI Agents with a Scientific Research Suite](<06_AstaBench Rigorous Benchmarking of AI Agents with a Scientific Research Suite.md>) | ICLR 2026 | Oral（Ai2官方文章确认；会务页面受限） | [本地PDF](<06_AstaBench Rigorous Benchmarking of AI Agents with a Scientific Research Suite.pdf>) |
| 7 | [τ²-Bench: Evaluating Conversational Agents in a Dual-Control Environment](<07_τ²-Bench Evaluating Conversational Agents in a Dual-Control Environment.md>) | ICML 2026 | Oral（作者公开报告确认；出版由PMLR确认） | [本地PDF](<07_τ²-Bench Evaluating Conversational Agents in a Dual-Control Environment.pdf>) |
| 8 | [Terminal-Bench: Benchmarking Agents on Hard, Realistic Tasks in Command Line Interfaces](<08_Terminal-Bench Benchmarking Agents on Hard Realistic Tasks in Command Line Interfaces.md>) | ICLR 2026 | 主会录用；展示等级未独立核验，不计入优选等级 | [本地PDF](<08_Terminal-Bench Benchmarking Agents on Hard Realistic Tasks in Command Line Interfaces.pdf>) |
| 9 | [Training a Generally Curious Agent](<09_Training a Generally Curious Agent.md>) | ICML 2025 | Oral候选（会务oral链接存在于外部导航但正文受限；暂不计入已核验等级） | [本地PDF](<09_Training a Generally Curious Agent.pdf>) |
