# Awesome-OpenClaw-Research [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

![](assets/banner.gif)

🦞 **OpenClaw** launched Nov 2025, hit 200k GitHub stars in **84 days**, and surpassed **330k stars** by March 2026. This repo collects **papers studying or built upon the OpenClaw ecosystem** — covering agent infrastructure, learning, safety, embodiment, social dynamics & domain applications. The questions are universal; OpenClaw is the lens.

<p align="center">
  <a href="#-papers"><img src="https://img.shields.io/badge/Papers-25%2B-blue?style=flat-square" alt="Papers"></a>
  <a href="https://github.com/openclaw/openclaw"><img src="https://img.shields.io/badge/OpenClaw-330k%2B%20Stars-yellow?style=flat-square" alt="Stars"></a>
  <a href="#-contributing"><img src="https://img.shields.io/badge/PRs-Welcome-brightgreen?style=flat-square" alt="PRs Welcome"></a>
</p>

---

## Table of Contents

- [Papers](#-papers) — **Core of this repo**
  - [Infrastructure & Systems](#infrastructure--systems)
  - [Learning & Evolution](#learning--evolution)
  - [Safety & Security](#safety--security)
  - [Agent Society](#agent-society)
  - [application](#application)
- [Architecture](#-architecture)
- [Ecosystem Timeline](#-ecosystem-timeline)
- [Other Resources](#-other-resources) — SDKs, tools, community, related repos
- [Contributing](#-contributing)

---

## 📄 Papers

> 25+ papers published in Feb–Mar 2026 alone. Each entry includes paper link, code (if available), and key highlights.

### Infrastructure & Systems

> Frameworks, OS paradigms, benchmarks, and protocol evaluation.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **OpenClaw as Language Infrastructure: A Case-Centered Survey of a Public Agent Ecosystem in the Wild (Survey)** | Preprints.org | 2026.03 | [![Preprints](https://img.shields.io/badge/202603.1060-b31b1b?style=flat-square)](https://www.preprints.org/manuscript/202603.1060) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **AgentOS: From Application Silos to a Natural Language-Driven Data Ecosystem** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.08938-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.08938) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **ClawGUI: A Unified Framework for Training, Evaluating, and Deploying GUI Agents** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.13428-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.11784) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/zju-real/ClawGUI)|
| **MCP-Atlas: A Large-Scale Benchmark for Tool-Use Competency with Real MCP Servers** | arXiv | 2026.01 | [![arXiv](https://img.shields.io/badge/2602.00933-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.00933) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **NanoClaw** | GitHub | 2026.01 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/qwibitai/nanoclaw) |
| **nanobot** | GitHub | 2026.02 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/HKUDS/nanobot) |
| **PicoClaw: Ultra-Efficient AI Assistant in Go** | GitHub | 2026.02 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/sipeed/picoclaw) |
| **Three Provinces and Six Ministries · Edict** | GitHub | 2026.02 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/cft0808/edict) |
| **CyberClaw: Next-Gen Transparent Agent Architecture** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/ttguy0707/CyberClaw) |

### Learning & Evolution

> Reinforcement learning, meta-learning, and self-improvement of agents.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **OpenClaw-RL: Train Any Agent Simply by Talking** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.10165) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/Gen-Verse/OpenClaw-RL) |
| **MetaClaw: Just Talk -- An Agent That Meta-Learns and Evolves in the Wild** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.17187-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.17187) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/aiming-lab/MetaClaw) |
| **Hermes-Agent** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/NousResearch/hermes-agent) |
| **SkillClaw: Let Skills Evolve Collectively with Agentic Evolver** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.17187-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.08377) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/AMAP-ML/SkillClaw) |
| **Hierarchical Memory Orchestration for Personalized Persistent Agents** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.01670) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **MemOS: A Memory OS for AI System** | arXiv | 2025.07 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2507.03724) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MemTensor/MemOS) |
| **OpenViking: The Context Database for AI Agents** | GitHub | 2026.01 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/volcengine/OpenViking) |
| **SemaClaw: A Step Towards General-Purpose Personal AI Agents through Harness Engineering** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.11548) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/midea-ai/SemaClaw) |
| **EvoMaster: A Foundational Evolving Agent Framework for Agentic Science at Scale** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.17406) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/sjtu-sai-agents/EvoMaster) |
| **StepPO: Step-Aligned Policy Optimization for Agentic Reinforcement Learning** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.10165-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.18401) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/AgentR1/Agent-R1) [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/AgentR1/Claw-R1)|
| **EvoClaw: Evaluating AI Agents on Continuous Software Evolution** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.13428-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.13428) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/Hydrapse/EvoClaw) [![HuggingFace](https://img.shields.io/badge/Dataset-FFD21E?style=flat-square&logo=huggingface&logoColor=000)](https://huggingface.co/datasets/hyd2apse/EvoClaw-data) |

### Safety & Security

> Attack benchmarks, defense frameworks, supply-chain security, and runtime protection.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **From Assistant to Double Agent: Formalizing and Benchmarking Attacks on OpenClaw for Personalized Local AI Agent** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.08412-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.08412) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/AstorYH/PASB) |
| **A Trajectory-Based Safety Audit of Clawdbot (OpenClaw)** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.14364-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.14364) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/tychenn/clawdbot_report) |
| **Formal Analysis and Supply Chain Security for Agentic AI Skills** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2603.00195-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.00195) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/qualixar/skillfortify) [![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=flat-square&logo=pypi)](https://pypi.org/project/skillfortify/) |
| **Don't Let the Claw Grip Your Hand: A Security Analysis and Defense Framework for OpenClaw** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.10387-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.10387) | [![Github](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/S2yyyy/OpenClaw-Analysis) |
| **OpenClaw PRISM: A Zero-Fork, Defense-in-Depth Runtime Security Layer for Tool-Augmented LLM Agents** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11853-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11853) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **Uncovering Security Threats and Architecting Defenses in Autonomous Agents: A Case Study of OpenClaw** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.12644-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.12644) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/NY1024/ClawGuard) |
| **Defensible Design for OpenClaw: Securing Autonomous Tool-Invoking Agents** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.13151-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.13151) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **Claw-Eval: Toward Trustworthy Evaluation of Autonomous Agents** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.12644-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.06132v1) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/claw-eval/claw-eval) |
| **ClawArena: Benchmarking AI Agents in Evolving Information Environments** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.12644-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.04202) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/aiming-lab/ClawArena) |
| **Taming OpenClaw: Security Analysis and Mitigation of Autonomous LLM Agent Threats** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.12644-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11619) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/antgroup/ClawAegis) |
| **ClawBench: Can AI Agents Complete Everyday Online Tasks?** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2603.12644-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.08523) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **Your Agent, Their Asset: A Real-World Safety Analysis of OpenClaw** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2602.02625-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.04759) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/UCSC-VLAA/CIK-Bench) |
| **ClawLess: A Security Model of AI Agents** | arXiv | 2026.04 | [![arXiv](https://img.shields.io/badge/2602.02625-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2604.06284v1) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square)|

### Agent Society

> Social behaviors, emergent norms, peer learning, and collective dynamics in agent populations.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **OpenClaw Agents on Moltbook: Risky Instruction Sharing and Norm Enforcement in an Agent-Only Social Network** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.02625-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.02625) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/manikm-114/OpenClaw-Agents-on-Moltbook) |
| **When AI Agents Teach Each Other: Discourse Patterns Resembling Peer Learning in the Moltbook Community** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.14477-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.14477) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **OpenClaw AI Agents as Informal Learners at Moltbook: Characterizing an Emergent Learning Community at Scale** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.18832-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.18832) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **When Openclaw Agents Learn from Each Other: Insights from Emergent AI Agent Communities for Human-AI Partnership in Education** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.16663-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.16663) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **MoChat: Reconnecting the World through AI Agents** | GitHub | 2026.02 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/HKUDS/MoChat) |
| **AgentPanel: The world’s first research-focused human-AI Agent collaborative discussion community** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/InternScience/AgentPanel) |
| **ClawTeam: Agent Swarm Intelligence** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/HKUDS/ClawTeam) |

### application

> Vertical applications, organized into embodied, scientific discovery, medical, and other directions.

#### Embodied Agents

> Robotics, physical embodiment, and ROS integration.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **RoboClaw: An Agentic Framework for Scalable Long-Horizon Robotic Tasks** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11558-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11558) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/RoboClaw-Robotics/RoboClaw) |
| **RoboClaw (MINT): Open-Source Embodied Intelligence Assistant** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MINT-SJTU/RoboClaw) |
| **ROSClaw: An OpenClaw ROS 2 Framework for Agentic Robot Control and Interaction** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11558-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.26997) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/PlaiPin/rosclaw) |
| **RoClaw: The Cerebellum — physical embodiment for AI agents** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/EvolvingAgentsLabs/RoClaw) |

#### Autonomous Driving and Aerial Systems

> Autonomous driving, aerial robotics, and vehicle-agent integration.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **StreamingClaw Technical Report** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11558-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.22120) | [![Website](https://img.shields.io/badge/Web-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://jackyu6.github.io/StreamingClaw-Page/) [![HuggingFace](https://img.shields.io/badge/Dataset-FFD21E?style=flat-square&logo=huggingface&logoColor=000)](https://huggingface.co/collections/LiAuto-Foundation-Model/streamingclaw) |
| **UAV-Claw** | GitHub | 2026.04 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://prince687028.github.io/UAV-Claw/) |

#### Scientific Discovery

> Automated research, distributed discovery, and life-science research platforms.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **Autonomous Agents Coordinating Distributed Discovery Through Emergent Artifact Exchange** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.14312-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.14312) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/lamm-mit/scienceclaw) |
| **From Agent-Only Social Networks to Autonomous Scientific Research: Lessons from OpenClaw and Moltbook, and the Architecture of ClawdLab and Beach.Science** | arXiv | 2026.02 | [![arXiv](https://img.shields.io/badge/2602.19810-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2602.19810) | [![GitHub](https://img.shields.io/badge/Beach.Science-181717?style=flat-square&logo=github)](https://github.com/moleculeprotocol/science.beach) [![GitHub](https://img.shields.io/badge/ClawdLab-181717?style=flat-square&logo=github)](https://github.com/bio-xyz/ClawdLab) |
| **ScienceClaw** | GitHub / Website | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/beita6969/ScienceClaw) [![Website](https://img.shields.io/badge/Web-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://scienceclaw.ai/) |
| **clawRxiv: Agent-Native Open Research Archive** | GitHub / Website | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/wu-yc/Claw4S_Stanford/tree/main) [![Website](https://img.shields.io/badge/Web-0A66C2?style=flat-square&logo=googlechrome&logoColor=white)](https://www.clawrxiv.io/) |
| **AutoResearchClaw:Chat an Idea. Get a Paper. Autonomous, Collaborative & Self-Evolving.** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/aiming-lab/AutoResearchClaw) |

#### Medical

> Clinical workflows, medical imaging, digital twins, and medical skill ecosystems.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **Autonomous Agent-Orchestrated Digital Twins (AADT): Leveraging the OpenClaw Framework for State Synchronization in Rare Genetic Disorders** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.27104-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.27104) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **MedOpenClaw: Auditable Medical Imaging Agents Reasoning over Uncurated Full Studies** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.24649-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.24649) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |
| **OpenClaw-Medical-Skills** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) |
| **When OpenClaw Meets Hospital: Toward an Agentic Operating System for Dynamic Clinical Workflows** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11721-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11721) | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) |

#### Other

> Other application directions such as education, knowledge work, and math learning.

| Title | Venue | Date | Paper | Code |
|-------|-------|------|-------|------|
| **Scaling Laws for Educational AI Agents** | arXiv | 2026.03 | [![arXiv](https://img.shields.io/badge/2603.11709-b31b1b?style=flat-square&logo=arxiv)](https://arxiv.org/abs/2603.11709) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/EduClaw-InnoSpark/AgentProfile) |
| **DenchClaw** | GitHub | 2026.02 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/DenchHQ/denchclaw) |
| **MathClaw** | GitHub | 2026.03 | ![N/A](https://img.shields.io/badge/N/A-grey?style=flat-square) | [![GitHub](https://img.shields.io/badge/Code-181717?style=flat-square&logo=github)](https://github.com/MathClaw-ruc/MathClaw) |

---

## 🏗 Architecture

```mermaid
flowchart LR
    subgraph Channels["📱 Channels"]
        direction TB
        C1[WhatsApp] ~~~ C2[Telegram] ~~~ C3[Discord] ~~~ C4[Slack] ~~~ C5["50+"]
    end

    subgraph Core["⚙️ Core"]
        direction TB
        Router[Message Router] --> Kernel[Agent Kernel]
        Kernel <--> LLM["LLM Backend\nClaude / GPT / Ollama"]
    end

    subgraph Memory["🧠 Memory"]
        direction TB
        M1[Session Context] ~~~ M2[Daily Notes] ~~~ M3[Long-term Memory] ~~~ M4[Semantic Search]
    end

    subgraph Extensions["🔌 Extensions"]
        direction TB
        E1["Skills (5,700+)"] ~~~ E2["MCP (3,200+)"] ~~~ E3[Plugins]
    end

    subgraph External["🌐 External"]
        direction TB
        X1[Moltbook] ~~~ X2[ROSClaw] ~~~ X3[RoboClaw]
    end

    Channels --> Core
    Core <--> Memory
    Core <--> Extensions
    Extensions --> External
```

---

## 📅 Ecosystem Timeline

```
2025.11 ─── Launch (ClawdBot / Moltbot → OpenClaw)
    │
2025.12 ─── ClawHub skill marketplace
    │
2026.01 ─── Moltbook (1.5M agents / 72h) ─── Academic paper boom (6 papers / 2 weeks)
    │
2026.02 ─── ClawHavoc attack ─── CVE-2026-25253 ─── 200k Stars (84 days)
    │         │
    │         └── Response: VirusTotal + audit mechanisms
    │
2026.03 ─── RL / Meta-Learning / Robotics papers ─── 330k Stars
    │
    └── ROSClaw Hackathon champion ─── v2026.3.13-1 (68th release)
              │
              └── WeChat official ClawBot plugin (03.22)
                    │
                    └── National Cybersecurity Advisory (China, 03.13)
```

<details>
<summary><b>Full timeline</b></summary>

| Date | Event |
|------|-------|
| 2025.11.24 | OpenClaw (formerly ClawdBot / Moltbot) launched |
| 2025.12 | ClawHub skill marketplace released |
| 2026.01 | Moltbook launched — 1.5M agents registered in 72h |
| 2026.01 | 6 academic papers produced in 2 weeks |
| 2026.02.02 | Risky Sharing & Norm Enforcement paper |
| 2026.02 | PASB security evaluation paper |
| 2026.02 | ClawHavoc supply chain attack — 1,184 malicious skills |
| 2026.02 | CVE-2026-25253 disclosed (RCE, CVSS 8.8) |
| 2026.02.16 | GitHub Stars crossed 200k (84 days) |
| 2026.02 | OpenClaw + VirusTotal security partnership |
| 2026.03 | OpenClaw-RL / MetaClaw / AgentOS / RoboClaw papers |
| 2026.03 | ROSClaw won SF OpenClaw Hackathon |
| 2026.03.13 | v2026.3.13-1 released (68th release) |
| 2026.03.13 | China National Cybersecurity Advisory |
| 2026.03.22 | WeChat official ClawBot plugin released |
| 2026.03 | GitHub Stars crossed 330k |

</details>

---

## 📦 Other Resources

<details>
<summary><b>Official Links</b></summary>

| Name | Link |
|------|------|
| OpenClaw Core | [github.com/openclaw/openclaw](https://github.com/openclaw/openclaw) |
| ClawHub Marketplace | [clawhub.com](https://clawhub.com) |
| Official Docs | [docs.openclaw.ai](https://docs.openclaw.ai) |

</details>

<details>
<summary><b>SDKs & Tools</b></summary>

| Name | Language | Description |
|------|----------|-------------|
| [openclaw-sdk](https://masteryodaa.github.io/openclaw-sdk/) | Python | Build & publish autonomous AI agents |
| [mcp-bridge-openclaw](https://www.npmjs.com/package/mcp-bridge-openclaw) | TypeScript | MCP multi-server bridge |
| [amor71/openclaw-mcp](https://github.com/amor71/openclaw-mcp) | TypeScript | Native MCP client |
| [henry-y/openclaw-paper-tools](https://github.com/henry-y/openclaw-paper-tools) | Python | OpenClaw arXiv paper reader |

</details>

<details>
<summary><b>Automated Research Tools</b></summary>

| Name | Link | Description |
|------|------|-------------|
| AutoResearchClaw | [GitHub](https://github.com/aiming-lab/AutoResearchClaw) | Fully autonomous 23-stage research pipeline: idea → experiment → conference-ready paper; multi-agent peer review |
| OpenClaw-Medical-Skills | [GitHub](https://github.com/FreedomIntelligence/OpenClaw-Medical-Skills) | 869 curated medical AI skills covering clinical work, genomics, drug discovery & bioinformatics |
| ScienceClaw | [GitHub](https://github.com/Zaoqu-Liu/ScienceClaw) | Autonomous research pipeline; 266+ domain skills; 77+ databases |
| ClawCures | [GitHub](https://github.com/agentcures/ClawCures) | AI campaign orchestrator for drug discovery; planner/critic loops; ADMET maps |
| clawRxiv | [Website](https://www.clawrxiv.io/) | Academic archive for AI agents — 383 agents, 1,827+ papers; affiliated with Stanford–Princeton Claw4S Conference (deadline Apr 30, 2026, prize $50,200) |
| Claw4Science (Claw4S) | [Website](https://claw4s.github.io/) | First agent-native scientific conference: submit executable skills, not papers; agent peer review; Stanford–Princeton co-organized |

</details>

<details>
<summary><b>Security References</b></summary>

| Name | Link |
|------|------|
| PASB Framework | [GitHub](https://github.com/AstorYH/PASB) |
| SkillFortify | [GitHub](https://github.com/qualixar/skillfortify) · [PyPI](https://pypi.org/project/skillfortify/) |
| SecureClaw | [GitHub](https://github.com/adversa-ai/secureclaw) |
| SlowMist Security Guide | [GitHub](https://github.com/slowmist/openclaw-security-practice-guide) |
| CVE-2026-25253 | [NVD](https://nvd.nist.gov/vuln/detail/CVE-2026-25253) |
| Security Guide | [bitdoze.com](https://www.bitdoze.com/openclaw-security-guide/) |

</details>

<details>
<summary><b>Benchmarks</b></summary>

| Name | Link | Description |
|------|------|-------------|
| PinchBench | [pinchbench.com](https://pinchbench.com) · [GitHub](https://github.com/pinchbench/skill) | 23 real-world tasks across 8 categories; automated + LLM judge grading |
| EvoClaw | [evo-claw.com](https://evo-claw.com) · [HuggingFace](https://huggingface.co/datasets/hyd2apse/EvoClaw-data) | Continuous software evolution benchmark; 7 repos / 5 languages / 98 milestones |

</details>


| Name | Link | Description |
|------|------|-------------|
| OpenClaw China | [BytePioneer-AI/openclaw-china](https://github.com/BytePioneer-AI/moltbot-china) | Domestic IM adaption (3,200+ Stars) |
| 中文教程 | [openclawgithub.cc](https://openclawgithub.cc) | Config & integration guides |
| Hello Claw | [Datawhale](https://datawhalechina.github.io/hello-claw/) | Datawhale tutorial |
| 中文站 | [clawcn.net](https://clawcn.net) | Domestic LLM guide |
| Learn OpenClaw | [learnopenclaw.com](https://learnopenclaw.com) | Learning platform |

</details>


> Know a great OpenClaw project we missed? Open a PR and help us keep this list growing!

| Repository | Stars | Description |
|------------|-------|-------------|
| [SamurAIGPT/awesome-openclaw](https://github.com/SamurAIGPT/awesome-openclaw) | 823 | Comprehensive list of OpenClaw resources, tools, skills, tutorials & articles |
| [mergisi/awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) | 830+ | 177 production-ready AI agent templates across 24 categories |
| [VoltAgent/awesome-openclaw-skills](https://github.com/VoltAgent/awesome-openclaw-skills) | — | Community curated skills collection |
| [community/openclaw-recipes](https://github.com/community/openclaw-recipes) | — | Common automation recipes |
| [templates/claw-templates](https://github.com/templates/claw-templates) | — | Starter templates for OpenClaw projects |
| [pranciskus/discourse-openclaw](https://github.com/pranciskus/discourse-openclaw) | NEW | Discourse forum integration with 12 tools |
| [wanikua/ByeByeClaw](https://github.com/wanikua/byebyeclaw) | NEW | One-command uninstaller for all Claw-family agents |

</details>

---

## 🤝 Contributing

Contributions are welcome! We especially need help with:

- **Papers** — Adding missing OpenClaw-related papers with proper links
- **Analysis** — Improving paper notes and highlights
- **Timeline** — Updating the ecosystem timeline with new events
