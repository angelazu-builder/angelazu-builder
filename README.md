# Hi there, I'm Angela Zu! 👋

[![University of Oxford](https://img.shields.io/badge/University_of_Oxford-Laidlaw_Scholar-002147.svg?style=flat&logo=university-of-oxford&logoColor=white)](https://www.ox.ac.uk/)
[![N1 AI Scholar](https://img.shields.io/badge/N1-AI_Scholar-FF4500.svg?style=flat)](#)
[![Focus](https://img.shields.io/badge/Focus-Agents_%26_Environments_%7C_Quant_Trading-8A2BE2.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![Trading & Markets](https://img.shields.io/badge/Trading-Interactive_Brokers_%7C_SEC_EDGAR-108548.svg)](#)

> 🛠️ **AI Systems Builder & Quantitative Researcher** · **University of Oxford** (Laidlaw Scholar) · **N1 AI Scholar**  
> 🔬 **Core Focus**: AI Agents & Execution Environments · Quantitative Trading & Event Engines · LLM Training Dynamics · Econometric Data Pipelines

---

## 🌟 Flagship Systems & Empirical Research

### 🧠 [1. Context-Length Order & LLM Training Dynamics (nanoGPT)](https://github.com/angelazu-builder/nanoGPT)
`Python` · `PyTorch (Apple Silicon / MPS)` · `Transformer Mechanics` · `Controlled Empirical Study` · `Preregistered Recovery`
* **Research Problem**: Does the temporal order of context lengths presented during training leave a persistent path-dependent deficit on an LLM's final capability, or is the apparent difference an artifact of recency bias and confounded evaluation?
* **What I Built & Key Findings**:
  - Engineered an inspectable **4.8M-parameter character-level Transformer** optimized for Apple Silicon (MPS backend) with modular data pipelines, diagnostic probes, and evaluation harnesses.
  - Executed a **three-iteration controlled empirical study**: evolved from an initial single-seed pilot to a 5-paired-seed design, culminating in a **formal preregistered recovery study** holding token budgets (4,096 tokens/step), paired seed initializations, data manifests, and AdamW optimizer trajectories invariant.
  - Uncovered that an initial severe descending deficit (**$+0.7570$ BPC** gap at $T=256$) **completely reversed to $-0.0485$ BPC** after a common $T=256$ recovery phase—ruling out strong persistent path dependence and demonstrating that final performance is dominated by recent context exposure.
* 🔗 [Repository](https://github.com/angelazu-builder/nanoGPT) | 📄 [Concise Technical Report (PDF)](https://github.com/angelazu-builder/nanoGPT/blob/main/training_dynamics_research/recovery_study/TECHNICAL_REPORT_CONCISE_final.pdf) | 📋 [Frozen Preregistration](https://github.com/angelazu-builder/nanoGPT/blob/main/training_dynamics_research/recovery_study/PREREGISTRATION.md)

---

### 📊 [2. OSEP Quantitative Research & AI Social Impact Intelligence](https://github.com/angelazu-builder/osep-quant-ai-social-impact)
`Python` · `OpenAI Responses API` · `Missing Data Econometrics` · `Multi-API Data Pipeline` · `Folium / Leaflet`
* **Research Problem**: Regulatory invisibility and missing data across micro-enterprises make evaluating social economy density and policy shocks challenging.
* **What I Built**: 
  - Standardized **3,096 master entities** across **7 REST/Bulk APIs** (Companies House, Charity Commission, FCA, 360Giving, Contracts Finder, IMD) using postcode-blocked Jaccard n-gram matching ($\ge 85\%$).
  - Evaluated **OpenAI Responses API (`web_search` tool)** vs **Chat Completions (`gpt-4o-mini`)**, demonstrating a 96% vs 32% accuracy jump and zero-hallucination web extraction.
  - Modeled the **2013 CIO Policy Shock** (+15,600% surge in CIOs, 61% drop in CLGs) and missing data theory (MCAR vs MAR/MNAR).
* 🔗 [Repository](https://github.com/angelazu-builder/osep-quant-ai-social-impact) | 🌐 [Live Interactive Maps](https://angelazu-builder.github.io/osep-quant-ai-social-impact/01-geospatial-intelligence/interactive-maps/population_density_map_v2.html) | 📄 [Empirical Paper](https://github.com/angelazu-builder/osep-quant-ai-social-impact/blob/main/04-ai-policy-technical-reports/openai_api_comparison_and_recommendation.md)

---

### 📈 [3. Event-Driven US Equities Mispricing & Trading Engine (Ongoing)](https://github.com/angelazu-builder/event-driven-trading)
`Python` · `Interactive Brokers (IBKR)` · `SEC EDGAR API` · `Streamlit` · `Probabilistic Valuation` · `Ongoing / WIP`
* **Research Problem**: Corporate events (earnings releases, guidance updates, Investor Days) shift fundamental cash flows faster than equity markets price them, but naive sentiment approaches suffer from severe look-ahead bias and ungrounded hallucinations.
* **What I Built & Key Edge**:
  - Implemented an end-to-end quantitative trading engine calculating the **Fundamental Revision ($FR$) vs Price Reaction ($PR$) Gap** to capture structural underreactions across 10-minute to multi-day horizons.
  - **Zero Look-Ahead Bias Ingestion**: Pre-event snapshot validation strictly locking consensus expectations prior to event execution; live SEC EDGAR REST API reader with sha256 content hashing and primary citation tracking.
  - **Quantified Probabilistic Valuation**: Structured thesis engine computing probabilistic Bull/Base/Bear scenarios, Expected Value ($EV$), return spreads, and explicit thesis break conditions.
  - **Automated Execution & Risk Limits**: Interactive Brokers (IBKR) paper order routing protected by strict portfolio guardrails (12.5% single-stock cap, 50% portfolio cap, spread <1.5%) and human-in-the-loop Streamlit UI.
* 🔗 [Repository](https://github.com/angelazu-builder/event-driven-trading) | 📄 [Architecture Specification](https://github.com/angelazu-builder/event-driven-trading/blob/main/docs/ARCHITECTURE.md)

---

### 🤖 [4. Autonomous AI Agents & Verification Environments (repo-organizer)](https://github.com/angelazu-builder/repo-organizer-skill)
`Python` · `AST Import Parsers` · `Invariant Baselines` · `Agentic Tool Execution` · `Safe Migration Pipeline`
* **Engineering Problem**: AI coding agents frequently propose hallucinated structural changes, break module imports, and generate unsubstantiated novelty claims without verifiable environment feedback.
* **What I Built**:
  - Developed an enterprise-grade AI Agent Skill and deterministic verification environment for autonomous repository audits and high-conversion landing page restructuring.
  - **6-Domain Invariant Verification Baseline** (`scripts/invariant_checker.py`): Programmatically captures and validates AST module imports, relative Markdown links, package entry points, and CI workflows.
  - **AST Safe Migration Pipeline** (`scripts/safe_migrate.py`): Performs dry-run simulations, atomic `git mv` operations, and instant automated `git reset` rollback on test or invariant failure.
  - **3-Layer External Novelty Audit**: Orchestrates GitHub Search API, OpenAlex/arXiv API, and web search to output deterministic 6-part proof tuples (`Claim -> Comparable -> Similarity -> Difference -> Evidence -> Confidence`).
* 🔗 [Repository](https://github.com/angelazu-builder/repo-organizer-skill) | 📦 [Skill Specification](https://github.com/angelazu-builder/repo-organizer-skill/blob/main/skills/repo-organizer/SKILL.md)

---

## 🛠️ Other Projects & Tools

* ⚡ **[gemini-live-multimodal-tutor](https://github.com/angelazu-builder/gemini-live-multimodal-tutor)**: Real-time multimodal conversational tutor built with the Gemini Live API for voice/visual problem solving (Google Cloud Hackathon 2026).
* 🗺️ **[oxfordshire-population-map](https://github.com/angelazu-builder/oxfordshire-population-map)**: Interactive geospatial portal mapping census demographic distributions and social enterprise density across UK postcodes (`OX1`–`OX49`) ([Live Map](https://angelazu-builder.github.io/oxfordshire-population-map/)).
* 📝 **[CrystalNotes](https://github.com/angelazu-builder/CrystalNotes)**: AI transcript intelligence pipeline transforming unstructured audio into deeply hierarchical, structured study notes.
* 🚀 **[tech-launch-promoter-skill](https://github.com/angelazu-builder/tech-launch-promoter-skill)**: AI Agent Skill for generating developer launch threads, Show HN submissions, and 15-second screen demo scripts.
* 🌌 **[Datawhale_AI4S](https://github.com/angelazu-builder/Datawhale_AI4S)**: Numba JIT-accelerated Kesten stochastic dynamics simulator & active learning candidate phase transition scanner.

---

## ⚙️ Technical Capabilities & Stack

- **AI Agents & Verification Environments**: Deterministic agent execution harnesses, AST-based import/dependency validation, 6-domain invariant checking, tool call schema verification, atomic migration pipelines.
- **Quantitative Trading & Financial Engineering**: Event-driven mispricing signals ($FR - PR$), SEC EDGAR live ingestion, abnormal return modeling, probabilistic scenario valuation ($EV$), Interactive Brokers (IBKR) API integration, risk management guardrails.
- **LLM Training Dynamics & Mechanics**: Context-length curricula, paired-seed experimental controls, preregistration protocols, BPC validation surfaces, Apple Silicon MPS profiling.
- **Quantitative Econometrics & Data Pipelines**: Multi-source REST/Bulk ETL pipelines, missing data theory (MCAR/MAR/MNAR), entity resolution (postcode-blocked Jaccard n-gram matching).
- **Languages & Frameworks**: Python (PyTorch, Numba, NumPy, SciPy, Pandas, Streamlit), JavaScript / TypeScript, HTML/CSS, SQL.

---

## 📫 Connect & Portfolios

- 🎓 **Affiliations**: University of Oxford (Laidlaw Scholar) · N1 AI Scholar
- 🧠 **nanoGPT Research**: [angelazu-builder/nanoGPT](https://github.com/angelazu-builder/nanoGPT)
- 📊 **OSEP Research Portal**: [osep-quant-ai-social-impact](https://github.com/angelazu-builder/osep-quant-ai-social-impact)
- 📈 **Quant Trading Engine (Ongoing)**: [event-driven-trading](https://github.com/angelazu-builder/event-driven-trading)
- 🤖 **Agent Environments**: [repo-organizer-skill](https://github.com/angelazu-builder/repo-organizer-skill)
- 🌐 **Interactive Maps**: [oxfordshire-population-map](https://angelazu-builder.github.io/oxfordshire-population-map/)
