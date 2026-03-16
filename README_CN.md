# Awesome Auto Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md) | [中文](README_CN.md)

> 精选的自动化科研开源项目列表 —— 覆盖文献综述、想法生成、实验执行、论文撰写与同行评审全流程。

**Star 数据最后验证时间：2026-03-16**

---

## 目录

- [端到端自主研究系统](#端到端自主研究系统)
- [深度调研与文献综合](#深度调研与文献综合)
- [自动化实验与代码智能体](#自动化实验与代码智能体)
- [Awesome Lists 与综述](#awesome-lists-与综述)
- [本列表与通用 AI Agent 列表的区别](#本列表与通用-ai-agent-列表的区别)
- [贡献指南](#贡献指南)

---

## 端到端自主研究系统

> 自动化完整研究生命周期：想法 → 实验 → 论文。

| 项目 | Stars | 简介 |
|------|-------|------|
| [autoresearch](https://github.com/karpathy/autoresearch) | ![Stars](https://img.shields.io/github/stars/karpathy/autoresearch?style=social) | Andrej Karpathy 出品。630 行 MIT 协议的 AI 智能体，能自主阅读训练脚本、提出假设、修改代码、运行实验并评估结果 —— 一夜之间自动跑数百个实验。 |
| [AI-Scientist](https://github.com/SakanaAI/AI-Scientist) | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=social) | 首个全自动开放式科学发现系统。自动完成想法生成、编码、实验运行和完整论文撰写。Sakana AI 出品。 |
| [Agent Laboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=social) | 端到端自主研究工作流，包含文献综述、实验和报告撰写的专用智能体。集成 arXiv、Hugging Face、Python 和 LaTeX。 |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=social) | NeurIPS 2025 Spotlight。完全自主系统，覆盖文献综述、假设生成、算法实现和可投稿论文准备。 |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=social) | AI-Scientist 升级版，使用 Agentic Tree Search。生成了首篇完全由 AI 撰写并通过同行评审被接收的 Workshop 论文。 |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | ![Stars](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep?style=social) | Claude Code skills 套件，用于自主 ML 研究：跨模型评审循环（Codex MCP）、想法发现流水线、实验自动化与论文撰写 —— 睡觉时全自动运行。 |

## 深度调研与文献综合

> 聚焦于自动信息收集、文献综述和报告生成。

| 项目 | Stars | 简介 |
|------|-------|------|
| [DeerFlow](https://github.com/bytedance/deer-flow) | ![Stars](https://img.shields.io/github/stars/bytedance/deer-flow?style=social) | 字节跳动出品。基于 LangGraph/LangChain 的开源 SuperAgent 框架，编排子智能体、记忆和沙箱，用于深度调研、代码生成和报告撰写。 |
| [STORM](https://github.com/stanford-oval/storm) | ![Stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social) | 斯坦福出品。LLM 驱动的知识管理系统，生成带引用的完整维基百科风格文章。支持 Co-STORM 人机协作研究。 |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | ![Stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social) | 自主深度网络和本地调研智能体。生成 5-6 页带引用的事实性报告，支持 PDF/Docx/Markdown 格式和多智能体研究工作流。 |
| [通义深度研究](https://github.com/Alibaba-NLP/DeepResearch) | ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=social) | 阿里巴巴出品。Agentic LLM（305 亿参数，33 亿激活），专为长周期深度信息检索设计。在 HLE、BrowseComp、WebWalkerQA、SimpleQA 等基准上达到 SOTA。 |
| [Open Deep Research](https://github.com/langchain-ai/open_deep_research) | ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=social) | LangChain 出品。开源深度调研框架，可配置 MCP 工具和搜索 API，支持多种 LLM 提供商。 |
| [PaperQA2](https://github.com/Future-House/paper-qa) | ![Stars](https://img.shields.io/github/stars/Future-House/paper-qa?style=social) | 面向科学文献的高精度 RAG 系统。动态检索全文论文并迭代优化回答。Future House 出品，发表于 ICLR。 |
| [DeepResearchAgent](https://github.com/SkyworkAI/DeepResearchAgent) | ![Stars](https://img.shields.io/github/stars/SkyworkAI/DeepResearchAgent?style=social) | 昆仑万维出品。层级多智能体系统，顶层规划智能体协调多个专业化底层智能体，用于深度调研和通用任务求解。 |
| [OpenScholar](https://github.com/AkariAsai/OpenScholar) | ![Stars](https://img.shields.io/github/stars/AkariAsai/OpenScholar?style=social) | 检索增强语言模型，搜索 4500 万篇开放获取论文并生成带引用的综合回答。发表于 Nature。OpenScholar-8B 超越 PaperQA2 和 Perplexity Pro。 |

## 自动化实验与代码智能体

> 自动化编码、实验执行和迭代优化。这些项目是自动化研究系统的"双手"。

| 项目 | Stars | 简介 |
|------|-------|------|
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ![Stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=social) | 最早的自主 AI 智能体框架之一。包含 Forge（智能体创建）、基准测试套件和用户友好界面。 |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=social) | AI 驱动的软件开发平台。自主编码智能体可编辑文件、运行命令、浏览网页并执行多步骤开发任务。SWE-Bench Verified 达 72%。 |
| [Aider](https://github.com/Aider-AI/aider) | ![Stars](https://img.shields.io/github/stars/Aider-AI/aider?style=social) | 终端中的 AI 结对编程。支持多文件编辑、Git 集成，兼容所有主流 LLM。广泛用作研究流水线中的编码基础设施。 |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) | ![Stars](https://img.shields.io/github/stars/SWE-agent/SWE-agent?style=social) | 普林斯顿出品。将 LLM 转化为能修复真实 GitHub Issue 的软件工程智能体。开创了 SWE-Bench 评测基准。 |

## Awesome Lists 与综述

> 自动化科研领域的精选集合和综述论文。

| 项目 | Stars | 简介 |
|------|-------|------|
| [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) | ![Stars](https://img.shields.io/github/stars/ai-boost/awesome-ai-for-science?style=social) | AI for Science 工具、库、论文、数据集和框架的精选列表，覆盖物理、化学、生物和材料科学等领域。 |

---

## 本列表与通用 AI Agent 列表的区别

本列表专注于**自动化科研流程**，而非通用 AI 智能体。我们收录的项目覆盖研究生命周期的一个或多个阶段：

```
文献综述 → 想法生成 → 新颖性检验 → 实验设计 →
代码实现 → 实验执行 → 结果分析 → 论文撰写 → 同行评审
```

通用编码智能体（OpenHands、Aider、SWE-agent）被收录是因为它们是实验执行阶段的关键基础设施。

---

## 贡献指南

欢迎提交 PR！请确保项目：
- **1,000+ GitHub stars**（或在顶级会议发表的特别知名项目）
- 与自动化科研直接相关
- 开源且仓库活跃

请按每个分类中的 star 数降序排列。

---

## Star 趋势

[![Star History Chart](https://api.star-history.com/svg?repos=karpathy/autoresearch,SakanaAI/AI-Scientist,bytedance/deer-flow,stanford-oval/storm,assafelovic/gpt-researcher,Alibaba-NLP/DeepResearch,langchain-ai/open_deep_research&type=Date)](https://star-history.com/#karpathy/autoresearch&SakanaAI/AI-Scientist&bytedance/deer-flow&stanford-oval/storm&assafelovic/gpt-researcher&Alibaba-NLP/DeepResearch&langchain-ai/open_deep_research&Date)

---

## 许可证

[CC0 1.0 Universal](LICENSE)
