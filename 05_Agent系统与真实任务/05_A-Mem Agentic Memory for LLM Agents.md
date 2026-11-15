# A-Mem: Agentic Memory for LLM Agents

[返回方向导读](README.md)

- 会议/期刊：NeurIPS 2025
- 展示级别：主会录用；未核验Oral/Spotlight，不计入优选等级
- 类型：pure method
- [论文页面](https://arxiv.org/abs/2502.12110)
- [在线PDF](https://arxiv.org/pdf/2502.12110)
- [本地PDF](<05_A-Mem Agentic Memory for LLM Agents.pdf>)
- [作者代码/项目入口](https://github.com/WujiangXu/A-mem)

## 核心内容与阅读价值

把经历转成带属性的笔记，动态建立关联并更新历史记忆，使存储和检索随任务演化。适合作为长期交互与记忆难度分析的轻量基线。

## 问题与研究连接

研究延伸：多跳、时间推理和干扰信息增多时，检索错误与记忆更新错误如何分别影响成功率；应统一token预算与检索调参集合。

## 4–6 张 3090 的复现判断

免权重训练；仓库提供Qwen2.5-3B、vLLM/Ollama/API路径及数据子集参数。单张3090起步合理（推断）；完整比较需计入建库调用成本。

## 核验记录

核验日期为 2026-11-13。

NeurIPS 2025正式PDF https://openreview.net/pdf/518e506d098a6c821c7e4ae97d1368f374fddac9.pdf 的首页及作者官方仓库确认会议；仓库已查运行示例。

PDF 状态：已下载（28页）。
