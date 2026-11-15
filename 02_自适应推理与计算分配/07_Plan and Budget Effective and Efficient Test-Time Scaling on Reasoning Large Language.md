# Plan and Budget: Effective and Efficient Test-Time Scaling on Reasoning Large Language Models

[返回方向导读](README.md)

- 会议/期刊：ICLR 2026
- 展示级别：主会录用（展示级别未核验）
- 类型：pure method
- [论文页面](https://proceedings.iclr.cc/paper_files/paper/2026/hash/ae8d4084f418bb51575c2ca6c658a05b-Abstract-Conference.html)
- [在线PDF](https://proceedings.iclr.cc/paper_files/paper/2026/file/ae8d4084f418bb51575c2ca6c658a05b-Paper-Conference.pdf)
- [本地PDF](<07_Plan and Budget Effective and Efficient Test-Time Scaling on Reasoning Large Language.pdf>)
- [作者代码/项目入口](https://github.com/junhongmit/P-and-B)

## 核心内容与阅读价值

先把问题拆成子问题，再依据各子问题估计的复杂度分配 token 预算。与按整题选预算的方法形成直接对照，也适合连接 Agent 的子任务执行。

## 问题与研究连接

分解和估计都占用预算，错误分解会把计算浪费在错误子任务上。可以比较固定总预算下的整题路由、子问题路由及实际正确率。

## 4–6 张 3090 的复现判断

方法无需重新训练底座。先在较小模型上复现分解和调度，再评估原文 32B、70B 等实验所需资源。

## 核验记录

核验日期为 2026-11-13。

[ICLR 正式论文页](https://proceedings.iclr.cc/paper_files/paper/2026/hash/ae8d4084f418bb51575c2ca6c658a05b-Abstract-Conference.html)确认出版、方法和代码入口。

PDF 状态：已下载（25页）。
