# UQLM: A Python Package for Uncertainty Quantification in Large Language Models

[返回方向导读](README.md)

- 会议/期刊：JMLR 2026
- 展示级别：期刊论文，无Oral/Highlight等级
- 类型：system/tool
- [论文页面](https://www.jmlr.org/papers/v27/25-1557.html)
- [在线PDF](https://www.jmlr.org/papers/volume27/25-1557/25-1557.pdf)
- [本地PDF](<07_UQLM A Python Package for Uncertainty Quantification in Large Language Models.pdf>)
- [作者代码/项目入口](https://github.com/cvs-health/uqlm)

## 核心内容与阅读价值

提供黑盒一致性、白盒概率、LLM评审和集成等回答级置信度估计工具。适合作为hardness预测的对照工具：模型的不确定性是否真的对应题目难度。

## 问题与研究连接

研究问题（推断）：高一致性可能是稳定地答错；置信度、题目难度、正确率三者不能直接画等号。该工具主要针对语言输出，迁移到多模态需验证。

## 4–6 张 3090 的复现判断

推断：可先复用已有输出，无需训练；白盒方法需token概率，黑盒方法需多次采样，有额外推理成本。4–6张3090适合多模型并行评测。

## 核验记录

核验日期为 2026-11-13。

https://www.jmlr.org/papers/v27/25-1557.html

PDF 状态：已下载（10页）。
