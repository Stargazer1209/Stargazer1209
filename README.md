# Hi, I'm Xiaokang Zhao (赵晓康) 👋

**CS Master's Student @ BUPT** · **Agent Runtime & LLM Systems Engineering**

I build deterministic **Agent Runtimes & Harnesses**, **Context/Memory Governance Pipelines**, and **Efficient Graph/Multimodal Models**. Previously worked on production multi-agent routing and long-context recall at **DiDi (L Lab)**.

[![Email](https://img.shields.io/badge/Email-xiaokang%40bupt.edu.cn-0284c7?style=flat-square)](mailto:xiaokang@bupt.edu.cn)
[![Publication](https://img.shields.io/badge/Paper-Complex_%26_Intelligent_Systems_(Springer)-0284c7?style=flat-square)](https://doi.org/10.1007/s40747-025-01985-8)
[![Focus](https://img.shields.io/badge/Focus-Agent_Harness_%7C_Context_Engineering_%7C_Efficient_LLMs-38bdf8?style=flat-square)](https://github.com/Stargazer1209)

---

### 🔬 Selected Research & Publications

- **[Complex & Intelligent Systems '25]** [**Efficient Knowledge Graph to Text Powered by LLGM: Linear Latent Graph Model**](https://doi.org/10.1007/s40747-025-01985-8) *(First Author, JCR Q2 / IF 4.5)*
  - Proposed **LLGM** integrating Multi-head Statistical Attention (MSA), Graph Latent Space Self-Attention (GLSA), and Graph Periodic Projector (GPP), reducing global attention complexity strictly from $O(N^2)$ to linear $O(N)$.
  - Cut parameter footprint by **20%–37%** and complex graph inference latency by **13%** ($p < 10^{-11}$), achieving **4.63 CIDEr (SOTA)** and **65.86% BLEU-4** on WebNLG v2.0.
  - 📦 Code & Modules: [`Stargazer1209/LLGM-research-data`](https://github.com/Stargazer1209/LLGM-research-data) · [`LLGMTeam/LLGM-research-data`](https://github.com/LLGMTeam/LLGM-research-data)

- **[B.Eng. Thesis — 1st Prize Award]** **VISTA-Q: Visual Self-Questioning Instruction Tuning for Multimodal LLMs**
  - Designed a dual-task instruction flow with a dedicated `[sqmd]` token and decoupled dual-pathway LoRA (`LLM-LoRA` + `ViT-LoRA`), outperforming LLaVA-v1.5 across VizWiz (54.2), SQA-I (68.6), VQA-T (58.6), and LLaVA-W (66.4) without extra human annotations.

---

### 🛠️ Systems & Engineering Highlights

- 🧬 **[`agent-microkernel`](https://github.com/Stargazer1209/agent-microkernel) (Harnessium)** — *Local-first, decoupled Agent Microkernel & Runtime*
  - Separates the deterministic daemon (`harnessiumd`: explicit state machine, multi-provider LLM gateway, sandboxed ACI primitives, tree-structured JSONL session branching) from thin clients (CLI/GUI) and composable `Workflow Packs` (`Skill + Lifecycle Hooks + Direct API + CLI + MCP`).
- 🚕 **Production Multi-Agent Governance @ DiDi L Lab** *(2025.10 – 2026.02)*
  - **Tool Routing & Interception**: Architected plan-layer memory validation and a 3-tier benchmark matrix for ride-hailing agents, achieving **100% interception** of out-of-bound dispatch requests with zero false positives on normal chat.
  - **Long-Session Context Recall**: Built a parallel Context Recall Agent over 20,000+ real sessions with 3-parameter adaptive gating, reaching **95.78% recall** and **85.29% precision** at **0.42s latency**.
- 🏎️ **[`f1-watch`](https://github.com/Stargazer1209/f1-watch)** — *Modern Formula 1 Telemetry Calendar & Glance Widgets for Android 13+*
  - Native **Kotlin + Jetpack Compose + Jetpack Glance** app featuring 11 constructor team themes, vector circuit maps, 4-tier self-healing offline cache, and a zero-pollution local build toolchain.

---

### 🧰 Tech Stack & Tooling

- **Agent & LLM Systems**: Agent Harness & Runtime Design · Context/Memory Engineering · MCP / Skill / Hook Orchestration · PyTorch · HuggingFace · vLLM
- **Languages & Native**: Python · C/C++ · Kotlin (Jetpack Compose) · Bash · SQL · Typst / LaTeX
- **Infra & Environment**: Linux (`systemd`, Headless CDP Automation, `tmux`) · Docker · Git

---

<sub>⚡ Linux + Windows Dual-Boot · Sky-Blue Enthusiast · Formula 1 Fan</sub>
