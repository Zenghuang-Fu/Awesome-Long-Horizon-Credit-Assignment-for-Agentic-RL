# Awesome-Long-Horizon-Credit-Assignment-for-Agentic-RL

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![image](./mainv1.png)

A curated list of papers, benchmarks, methods, and resources for **Long-Horizon Credit Assignment in Agentic Reinforcement Learning**.

---

## 📢 News

- 🚀 2026-05-27: Repository initialized.
- 📝 2026-05-28: Taxonomy for long-horizon credit assignment released.

---

## 📚 Table of Contents

- [🏛️ Awesome-Long-Horizon-Credit-Assignment-for-Agentic-RL](#-awesome-long-horizon-credit-assignment-for-agentic-rl)
  - [📢 News](#-news)
  - [🧭 Taxonomy](#-taxonomy)
    - [1️⃣ Trajectory-level Credit Assignment](#1-trajectory-level-credit-assignment)
    - [2️⃣ Step-level and Turn-level Credit Assignment](#2-step-level-and-turn-level-credit-assignment)
    - [3️⃣ Branch-level and Tree-structured Credit Assignment](#3-branch-level-and-tree-structured-credit-assignment)
    - [4️⃣ Action-level and Tool-use Credit Assignment](#4-action-level-and-tool-use-credit-assignment)
    - [5️⃣ Retrieval and Evidence-level Credit Assignment](#5-retrieval-and-evidence-level-credit-assignment)
    - [6️⃣ Memory-level and Skill-level Credit Assignment](#6-memory-level-and-skill-level-credit-assignment)
    - [7️⃣ Advantage Estimation and Policy Optimization under Long Horizons](#7-advantage-estimation-and-policy-optimization-under-long-horizons)
    - [8️⃣ Benchmarks and Evaluation Protocols](#8-benchmarks-and-evaluation-protocols)
  - [📄 Papers](#-papers)
  - [🤝 Contributing](#-contributing)
  - [⭐ Star History](#-star-history)
  - [📑 Citation](#-citation)

---

## 🧭 Taxonomy

### 1️⃣ Trajectory-level Credit Assignment

Final-outcome rewards, sparse rewards, trajectory-level verification, and success/failure-based optimization.

### 2️⃣ Step-level and Turn-level Credit Assignment

Process rewards, step-level verifiers, dense feedback, intermediate supervision, and turn-level rewards.

### 3️⃣ Branch-level and Tree-structured Credit Assignment

Tree search, multi-path reasoning, branch-level rewards, node-level value estimation, and hierarchical advantage estimation.

### 4️⃣ Action-level and Tool-use Credit Assignment

Credit assignment for tool calls, code execution, API use, browser actions, and environment interactions.

### 5️⃣ Retrieval and Evidence-level Credit Assignment

Search agents, query-level rewards, document utility estimation, evidence-level feedback, and retrieval-augmented RL.

### 6️⃣ Memory-level and Skill-level Credit Assignment

Reusable skills, reflection memory, failure memory, option learning, hierarchical policies, and cross-trajectory credit assignment.

### 7️⃣ Advantage Estimation and Policy Optimization under Long Horizons

Long-horizon advantage estimation, variance reduction, entropy regularization, adaptive KL, reward normalization, and stable policy optimization.

### 8️⃣ Benchmarks and Evaluation Protocols

Benchmarks, environments, and evaluation protocols for long-horizon agentic RL and credit assignment.

---

## 📄 Papers

### 1️⃣ Trajectory-level Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155) | RLHF | 2022 | - | NeurIPS |
| [DeepSeekMath](https://arxiv.org/abs/2402.03300) | GRPO | 2024 | [Code](https://github.com/deepseek-ai/DeepSeek-Math) | arXiv |
| Paper Title | Method Name | Year | [Code](#) | Venue |

### 2️⃣ Step-level and Turn-level Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Turn-level advantage estimation with ppo for improved multi-turn rl in agentic llms](https://aclanthology.org/2026.findings-eacl.328.pdf) | Turn-ppo | 2026 | - | EACL |
|[Step-level advantage assignment for long-horizon agents via trajectory graph](https://aclanthology.org/2026.findings-eacl.247.pdf)|Salt|2026|-|EACL|
| Paper Title | Method Name | Year | [Code](#) | Venue |

### 3️⃣ Branch-level and Tree-structured Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Tree search for llm agent reinforcement learning](https://arxiv.org/pdf/2509.21240) | Tree-GRPO | 2026 | [Code](https://github.com/AMAP-ML/Tree-GRPO) | ICLR |
|[Tree-structured reinforcement fine-tuning for self-evolving embodied agents](https://proceedings.neurips.cc/paper_files/paper/2025/file/7103cd82de95a7b30983fcf74ba499ac-Paper-Conference.pdf)|SEEA-R1|2026|[Code](https://seea-r1.github.io/)|NeurIPS|
| Paper Title | Method Name | Year | [Code](#) | Venue |

### 4️⃣ Action-level and Tool-use Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [ReAct](https://arxiv.org/abs/2210.03629) | ReAct | 2022 | [Code](https://github.com/ysymyth/ReAct) | ICLR |

### 5️⃣ Retrieval and Evidence-level Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Expanding Exploration for LLM Agents via Retrieval-Augmented Policy Optimization](https://arxiv.org/pdf/2603.03078)|RAPO|2026|-|KDD|

### 6️⃣ Memory-level and Skill-level Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Reflexion](https://arxiv.org/abs/2303.11366) | Reflexion | 2023 | [Code](https://github.com/noahshinn/reflexion) | NeurIPS |

### 7️⃣ Advantage Estimation and Policy Optimization under Long Horizons

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Group-in-Group Policy Optimization for LLM Agent Training](https://proceedings.neurips.cc/paper_files/paper/2025/file/420c9f777c0b4f78d515e53cf74d58b2-Paper-Conference.pdf) | GIGPO | 2025 | [Code](https://github.com/langfengQ/verl-agent) | NeurIPS |
| [Adaptive tree policy optimization for multi-turn medical dialogue](https://arxiv.org/pdf/2603.02216)|ATPO|2026|-|ICLR|
|[Tree-Structured Advantage Redistribution for Group-Based RL](https://arxiv.org/abs/2601.03703)|TreeAdv|2026|-|arxiv|
|[End-to-end policy optimization for gui agents with experience replay](https://arxiv.org/pdf/2505.16282?)|Arpo|2025|-|arxiv|
|[Agentic reinforced policy optimization](https://arxiv.org/pdf/2507.19849)|ARPO|2025|-|arxiv|
|[Agentic entropy-balanced policy optimization](https://arxiv.org/pdf/2510.14545)|AEPO|2025|-|arxiv|
|[Information Gain-based Policy Optimization: A Simple and Effective Approach for Multi-Turn LLM Agents](https://arxiv.org/pdf/2510.14967?)|IGPO|2026|[Code](https://github.com/GuoqingWang1/IGPO)|ICLR|


### 8️⃣ Benchmarks and Evaluation Protocols

| 📖 Title | 🛠 Benchmark / Environment | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| WebShop | Web Interaction Benchmark | 2022 | [Code](https://github.com/princeton-nlp/WebShop) | NeurIPS |

---

## 🤝 Contributing

- Add missing papers, benchmarks, or code repositories.
- Correct metadata, links, venues, or dates.
- Suggest better taxonomy improvements.
- Open issues for discussion.

---

## ⭐ Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Zenghuang-Fu/Awesome-Long-Horizon-Credit-Assignment-for-Agentic-RL&type=Date)](https://www.star-history.com/#Zenghuang-Fu/Awesome-Long-Horizon-Credit-Assignment-for-Agentic-RL&Date)
}
