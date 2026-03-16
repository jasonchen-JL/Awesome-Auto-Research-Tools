# Awesome Auto Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English](README.md) | [中文](README_CN.md)

> A curated list of open-source projects that automate scientific research — from literature review to idea generation, experiment execution, paper writing, and peer review.

**Star counts last verified: 2026-03-16**

---

## Table of Contents

- [End-to-End Autonomous Research Systems](#end-to-end-autonomous-research-systems)
- [Deep Research & Literature Synthesis](#deep-research--literature-synthesis)
- [Automated Experiment & Code Agent](#automated-experiment--code-agent)
- [Awesome Lists & Surveys](#awesome-lists--surveys)
- [How This Differs from General AI Agent Lists](#how-this-differs-from-general-ai-agent-lists)
- [Contributing](#contributing)

---

## End-to-End Autonomous Research Systems

> Projects that automate the full research lifecycle: idea → experiment → paper.

| Project | Stars | Description |
|---------|-------|-------------|
| [autoresearch](https://github.com/karpathy/autoresearch) | ![Stars](https://img.shields.io/github/stars/karpathy/autoresearch?style=social) | By Andrej Karpathy. 630-line MIT-licensed AI agent that reads its own training script, forms hypotheses, modifies code, runs experiments, and evaluates results — autonomously running hundreds of experiments overnight. |
| [AI-Scientist](https://github.com/SakanaAI/AI-Scientist) | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist?style=social) | The first comprehensive system for fully automated open-ended scientific discovery. Automates idea generation, coding, experiment execution, and full manuscript writing. By Sakana AI. |
| [Agent Laboratory](https://github.com/SamuelSchmidgall/AgentLaboratory) | ![Stars](https://img.shields.io/github/stars/SamuelSchmidgall/AgentLaboratory?style=social) | End-to-end autonomous research workflow with specialized agents for literature review, experimentation, and report writing. Integrates arXiv, Hugging Face, Python, and LaTeX. |
| [AI-Researcher](https://github.com/HKUDS/AI-Researcher) | ![Stars](https://img.shields.io/github/stars/HKUDS/AI-Researcher?style=social) | NeurIPS 2025 Spotlight. Fully autonomous system covering literature review, hypothesis generation, algorithm implementation, and publication-ready manuscript preparation. |
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | ![Stars](https://img.shields.io/github/stars/SakanaAI/AI-Scientist-v2?style=social) | Upgraded version using agentic tree search. Generated the first workshop paper written entirely by AI and accepted through peer review. Removes reliance on human-authored templates. |
| [ARIS](https://github.com/wanshuiyin/Auto-claude-code-research-in-sleep) | ![Stars](https://img.shields.io/github/stars/wanshuiyin/Auto-claude-code-research-in-sleep?style=social) | Claude Code skills for autonomous ML research: cross-model review loops (Codex MCP), idea discovery pipelines, experiment automation, and paper writing — all running while you sleep. |

## Deep Research & Literature Synthesis

> Projects focused on automated information gathering, literature review, and report generation.

| Project | Stars | Description |
|---------|-------|-------------|
| [DeerFlow](https://github.com/bytedance/deer-flow) | ![Stars](https://img.shields.io/github/stars/bytedance/deer-flow?style=social) | ByteDance. Open-source SuperAgent harness built on LangGraph/LangChain. Orchestrates sub-agents, memory, and sandboxes for deep research, code generation, and report writing. |
| [STORM](https://github.com/stanford-oval/storm) | ![Stars](https://img.shields.io/github/stars/stanford-oval/storm?style=social) | Stanford. LLM-powered knowledge curation system that generates full-length Wikipedia-like articles with citations. Features Co-STORM for collaborative human-AI research. |
| [GPT Researcher](https://github.com/assafelovic/gpt-researcher) | ![Stars](https://img.shields.io/github/stars/assafelovic/gpt-researcher?style=social) | Autonomous agent for deep web & local research. Generates 5-6 page factual reports with citations in PDF/Docx/Markdown. Supports multi-agent research workflows. |
| [Tongyi DeepResearch](https://github.com/Alibaba-NLP/DeepResearch) | ![Stars](https://img.shields.io/github/stars/Alibaba-NLP/DeepResearch?style=social) | Alibaba. Agentic LLM (30.5B params, 3.3B activated) for long-horizon deep information-seeking. SOTA on HLE, BrowseComp, WebWalkerQA, SimpleQA benchmarks. |
| [Open Deep Research](https://github.com/langchain-ai/open_deep_research) | ![Stars](https://img.shields.io/github/stars/langchain-ai/open_deep_research?style=social) | LangChain. Open-source deep research framework with configurable MCP tools and search APIs. Supports a wide range of LLM providers. |
| [PaperQA2](https://github.com/Future-House/paper-qa) | ![Stars](https://img.shields.io/github/stars/Future-House/paper-qa?style=social) | High-accuracy RAG for scientific documents. Dynamically retrieves full-text papers and iterates on answers. By Future House. Published at ICLR. |
| [DeepResearchAgent](https://github.com/SkyworkAI/DeepResearchAgent) | ![Stars](https://img.shields.io/github/stars/SkyworkAI/DeepResearchAgent?style=social) | Skywork. Hierarchical multi-agent system with top-level planning agent coordinating specialized lower-level agents for research and general-purpose task solving. |
| [OpenScholar](https://github.com/AkariAsai/OpenScholar) | ![Stars](https://img.shields.io/github/stars/AkariAsai/OpenScholar?style=social) | Retrieval-augmented LM that searches 45M open-access papers and synthesizes citation-backed responses. Published in Nature. OpenScholar-8B outperforms PaperQA2 and Perplexity Pro. |

## Automated Experiment & Code Agent

> Projects that automate coding, experiment execution, and iterative optimization. These serve as the "hands" of auto-research systems.

| Project | Stars | Description |
|---------|-------|-------------|
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | ![Stars](https://img.shields.io/github/stars/Significant-Gravitas/AutoGPT?style=social) | One of the earliest autonomous AI agent frameworks. Includes Forge for agent creation, benchmarking suite, and user-friendly UI. |
| [OpenHands](https://github.com/All-Hands-AI/OpenHands) | ![Stars](https://img.shields.io/github/stars/All-Hands-AI/OpenHands?style=social) | AI-driven software development platform. Autonomous coding agents that edit files, run commands, browse web, and execute multi-step dev tasks. 72% on SWE-Bench Verified. |
| [Aider](https://github.com/Aider-AI/aider) | ![Stars](https://img.shields.io/github/stars/Aider-AI/aider?style=social) | AI pair programming in your terminal. Supports multi-file edits, git integration, and works with all major LLMs. Widely used as the coding backbone in research pipelines. |
| [SWE-agent](https://github.com/SWE-agent/SWE-agent) | ![Stars](https://img.shields.io/github/stars/SWE-agent/SWE-agent?style=social) | Princeton. Turns LLMs into software engineering agents that fix real GitHub issues. Pioneered the SWE-Bench benchmark for evaluating coding agents. |

## Awesome Lists & Surveys

> Curated collections and survey papers on the auto-research landscape.

| Project | Stars | Description |
|---------|-------|-------------|
| [awesome-ai-for-science](https://github.com/ai-boost/awesome-ai-for-science) | ![Stars](https://img.shields.io/github/stars/ai-boost/awesome-ai-for-science?style=social) | Curated list of AI tools, libraries, papers, datasets, and frameworks for scientific discovery across physics, chemistry, biology, and materials. |

---

## How This Differs from General AI Agent Lists

This list focuses specifically on **automating the scientific research process** — not general-purpose AI agents. We include projects that target one or more stages of the research lifecycle:

```
Literature Review → Idea Generation → Novelty Check → Experiment Design →
Code Implementation → Experiment Execution → Result Analysis → Paper Writing → Peer Review
```

General-purpose coding agents (OpenHands, Aider, SWE-agent) are included because they serve as critical infrastructure for the experiment execution stage.

---

## Contributing

PRs welcome! Please ensure the project:
- Has **1,000+ GitHub stars** (or is exceptionally notable with a top-venue publication)
- Is directly related to automating scientific research
- Is open-source with an active repository

Please keep entries sorted by star count (descending) within each category.

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=karpathy/autoresearch,SakanaAI/AI-Scientist,bytedance/deer-flow,stanford-oval/storm,assafelovic/gpt-researcher,Alibaba-NLP/DeepResearch,langchain-ai/open_deep_research&type=Date)](https://star-history.com/#karpathy/autoresearch&SakanaAI/AI-Scientist&bytedance/deer-flow&stanford-oval/storm&assafelovic/gpt-researcher&Alibaba-NLP/DeepResearch&langchain-ai/open_deep_research&Date)

---

## License

[CC0 1.0 Universal](LICENSE)
