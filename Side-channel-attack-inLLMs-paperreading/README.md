# 大模型侧信道攻击论文阅读笔记

本仓库用于系统整理和记录我对 **大语言模型（Large Language Models, LLMs）侧信道攻击** 相关研究的阅读、理解和思考。  
所有笔记均为个人原创，欢迎交流与引用（请注明出处）。

> 🔍 侧信道攻击（Side-Channel Attack）指通过非直接方式（如时序、缓存、功耗、电磁辐射等）推断模型内部状态或敏感信息。

>本项目主要是针对大模型中的侧信道攻击的相关论文阅读的一些笔记 


---

## 📚 论文笔记目录

| 序号 | 日期 | 论文标题 | 笔记 | 发表日期（原文地址） |
| :--- | :--- | :--- | :--- | :--- |
| 1 | 2026-01-10 | InputSnatch: Stealing Input in LLM Services via Timing Side-Channel Attacks | [笔记](notes/001-InputSnatch%20Stealing%20Input%20in%20LLM%20Services%20via%20Timing%20Side-Channel%20Attacks.md) | [2024年11月](https://arxiv.org/pdf/2411.18191) |
| 2 | 2026-01-13 | Whisper Leak: A Side-channel Attack On Large Language Models | [笔记](notes/002-Whisper-Leak.md) | [2025年11月](https://arxiv.org/pdf/2511.03675) |
| 3 | 2026-01-16 | The early bird catches the leak: Unveiling timing side channels in llm serving systems | [笔记](notes/003-Early-Brid.md) | [2025年10月](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11206380) |
| 4 | 2026-01-19 | I Know What You Asked: Prompt Leakage via KV-Cache Sharing in Multi-Tenant LLM Serving | [笔记](notes/004-I-Know-What-You-Asked.md) | [2025年2月（ndss）](https://www.ndss-symposium.org/wp-content/uploads/2025-1772-paper.pdf) |
| 5 | 2026-01-24 | Selective KV-Cache Sharing to Mitigate Timing Side-Channels in LLM Inference | [笔记](notes/005-SafeKV.md) | [2025年8月](https://arxiv.org/pdf/2508.08438) |
| 6 | 2026-01-27 | I Know What You Said: Unveiling Hardware Cache Side-Channels in Local Large Language Model Inference | [笔记](notes/006-Know-You-Said.md) | [2025年6月](https://arxiv.org/pdf/2505.06738) |
| 7 | 2026-02-03 | Time Will Tell: Timing Side Channels via Output Token Count in Large Language Models | [笔记](notes/007-Time-Will-Tell.md) | [2024年12月](https://arxiv.org/pdf/2412.15431) |
| 8 | 2026-02-12 | Wiretapping LLMs: Network Side-Channel Attacks on Interactive LLM Services | [笔记](notes/008-Wiretapping) | [2025年02月](https://eprint.iacr.org/2025/167.pdf) |
| 9 | 2026-03-05 | Side-Channel  Attacks  in  Multi-Tenant Cloud  Environments:  Prevention  & Mitigation | [笔记](notes/009-Ijisem.md) | [2025年04月](https://ijisem.com/journal/index.php/ijisem/article/view/291/267) |
| 10 | 2026-08-14 | SemShareKV: Efficient KVCache Sharing for Semantically Similar Prompts via Token-Level LSH Matching | [笔记](notes/010-SemShareKV.md) | [2025年02月](https://arxiv.org/pdf/2509.24832) |
| ... | ... | ... | ... |


 
---

## 🗂 仓库结构

.
├── README.md # 本说明文件

├── notes/ # 每篇论文的详细阅读笔记（Markdown）

├── summaries/ # （可选）按主题/技术路线整理的综述

└── references.bib # （可选）BibTeX 引用库


## 一些提示词：

```markdown
根据网络搜索给出该文章的以下信息
**作者信息**
（包含作者的背景，研究领域，是否是某个领域的大牛等等）
**论文发表时间** 

**摘要**
（一句话总结）
```

```markdown
## 三、方法是怎么实现的？(How does it work?)
从以下几个方面说明：
### 1. 架构  （画出流程图，并注明参考的论文的哪一张图）
### 2. 关键算法  
### 3. 关键公式 (Key Formulas)
```

```markdown
## 四、实验效果 (Experimental Results)
### 1. 实验设置 (Experimental Setup)
### 2. 主要结果 (Main Results)
### 3. 消融实验与关键发现 (Ablation Studies & Key Findings)
```

```markdown
## 五. 优点与局限性 
### ✅ 1.优点 
### ⚠️ 2.局限性（研究边界与待解问题）
```