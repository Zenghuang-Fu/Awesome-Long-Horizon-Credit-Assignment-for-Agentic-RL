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
| [Let's Verify Step by Step](https://arxiv.org/abs/2305.20050) | Process Reward Model | 2023 | - | arXiv |
| Paper Title | Method Name | Year | [Code](#) | Venue |

### 3️⃣ Branch-level and Tree-structured Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Tree of Thoughts](https://arxiv.org/abs/2305.10601) | Tree of Thoughts | 2023 | [Code](https://github.com/princeton-nlp/tree-of-thought-llm) | NeurIPS |
| Paper Title | Method Name | Year | [Code](#) | Venue |

### 4️⃣ Action-level and Tool-use Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [ReAct](https://arxiv.org/abs/2210.03629) | ReAct | 2022 | [Code](https://github.com/ysymyth/ReAct) | ICLR |

### 5️⃣ Retrieval and Evidence-level Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [RAG](https://arxiv.org/abs/2005.11401) | Retrieval-Augmented Generation | 2020 | - | NeurIPS |

### 6️⃣ Memory-level and Skill-level Credit Assignment

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [Reflexion](https://arxiv.org/abs/2303.11366) | Reflexion | 2023 | [Code](https://github.com/noahshinn/reflexion) | NeurIPS |

### 7️⃣ Advantage Estimation and Policy Optimization under Long Horizons

| 📖 Title | 🛠 Model / Method | 📅 Date | 💻 Code | 🏛 Venue |
| :--- | :---: | :---: | :---: | :---: |
| [PPO](https://arxiv.org/abs/1707.06347) | PPO | 2017 | - | arXiv |

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
