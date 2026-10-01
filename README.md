# Hi there, I'm Angela Zu! 👋

[![University of Oxford](https://img.shields.io/badge/University_of_Oxford-Laidlaw_Scholar-002147.svg?style=flat&logo=university-of-oxford&logoColor=white)](https://www.ox.ac.uk/)
[![LLM Training Dynamics](https://img.shields.io/badge/Focus-LLM_Dynamics_%26_AI4S-8A2BE2.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![AI Agents](https://img.shields.io/badge/AI_Agents-Antigravity_%26_Gemini-FF6F00.svg)](#)

> 🛠️ **AI Systems Builder & Researcher at the University of Oxford** (Laidlaw Scholar)  
> 🔬 **Core Focus**: LLM Training Dynamics & Mechanics · Quantitative Econometrics & Data Pipelines · AI for Science & Stochastic Physics · Agentic Systems

---

## 🌟 Flagship Systems & Empirical Research

### 🧠 [1. Context-Length Order & LLM Training Dynamics (nanoGPT)](https://github.com/angelazu-builder/nanoGPT)
`Python` · `PyTorch (Apple Silicon / MPS)` · `Transformer Mechanics` · `Preregistered Recovery Study` · `ICML-Style Preprint`
* **Research Problem**: Does the temporal order of context lengths presented during training leave a persistent path-dependent deficit on an LLM's final capability, or is the apparent difference an artifact of recency bias and confounded evaluation?
* **What I Built & Key Findings**:
  - Engineered an inspectable **4.8M-parameter character-level Transformer** optimized for Apple Silicon (MPS backend) with modular data pipelines, diagnostic probes, and evaluation harnesses.
  - Executed a **three-iteration controlled empirical study**: evolved from an initial single-seed pilot to a 5-paired-seed design, culminating in a **formal preregistered recovery study** holding token budgets (4,096 tokens/step), paired seed initializations, data manifests, and AdamW optimizer trajectories invariant.
  - Uncovered that an initial severe descending deficit (**$+0.7570$ BPC** gap at $T=256$) **completely reversed to $-0.0485$ BPC** after a common $T=256$ recovery phase—ruling out strong persistent path dependence and demonstrating that final performance is dominated by recent context exposure.
* 🔗 [Repository](https://github.com/angelazu-builder/nanoGPT) | 📄 [Concise Technical Report (PDF)](https://github.com/angelazu-builder/nanoGPT/blob/main/training_dynamics_research/recovery_study/TECHNICAL_REPORT_CONCISE_final.pdf) | 📋 [Frozen Preregistration](https://github.com/angelazu-builder/nanoGPT/blob/main/training_dynamics_research/recovery_study/PREREGISTRATION.md) | 📄 [ICML Paper Preprint (PDF)](https://github.com/angelazu-builder/nanoGPT/blob/main/output/pdf/context_order_recovery_icml2026_final.pdf)

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

### 🌌 [3. Candidate Phase Transitions in Wealth Inequality (AI for Science)](https://github.com/angelazu-builder/Datawhale_AI4S)
`Python` · `Numba JIT` · `Kesten Stochastic Dynamics` · `Active Learning (UCB+GP)` · `World Bank API Calibration`
* **Research Problem**: Identifying non-continuous candidate phase transition thresholds in high-dimensional Kesten wealth dynamics ($W_{t+1} = A_t \cdot W_t + B_t$) without high-dimensional grid search bottlenecks.
* **Key Innovations**:
  - Implemented a Numba JIT-accelerated simulator ($N=100,000$, $T=500$) with **Active Learning Agents (UCB + Gaussian Process Surrogate)** to discover candidate phase transitions at $R^* = p/c \approx 0.15 \sim 0.20$.
  - Conducted **Finite-Size Scaling ($N \in [5k, 100k]$)** convergence proofs, Hill/Newman MLE tail fitting, and Bootstrap 95% Confidence Intervals.
  - Discovered two emergent phenomena: **Absorbing Boundary Structural Collapse** ($R^2 < 0.50$) and **Keynesian MPC Power-Law Breakdown** ($c(W) \sim W^{-\alpha}$).
  - Calibrated parameters with World Bank API macro data for US and China historical Gini coefficients.
* 🔗 [Repository](https://github.com/angelazu-builder/Datawhale_AI4S) | 📄 [Research Report (PDF/Docx)](https://github.com/angelazu-builder/Datawhale_AI4S/blob/main/docs/submission/03_%E5%AE%8C%E6%95%B4%E7%A0%94%E7%A9%B6%E6%8A%A5%E5%91%8A_Final_Report_v1.1.0.md) | 🌐 [English Readme](https://github.com/angelazu-builder/Datawhale_AI4S/blob/main/README_EN.md)

---

## 🛠️ Other Projects & Tools

* 🤖 **[repo-organizer-skill](https://github.com/angelazu-builder/repo-organizer-skill)**: AI Agent Skill for automated repository audits, AST import analysis, invariant baselining, and high-conversion landing page restructuring.
* ⚡ **[gemini-live-multimodal-tutor](https://github.com/angelazu-builder/gemini-live-multimodal-tutor)**: Real-time multimodal conversational tutor built with the Gemini Live API for voice/visual problem solving (Google Cloud Hackathon 2026).
* 🗺️ **[oxfordshire-population-map](https://github.com/angelazu-builder/oxfordshire-population-map)**: Interactive geospatial portal mapping census demographic distributions and social enterprise density across UK postcodes (`OX1`–`OX49`) ([Live Map](https://angelazu-builder.github.io/oxfordshire-population-map/)).
* 📝 **[CrystalNotes](https://github.com/angelazu-builder/CrystalNotes)**: AI transcript intelligence pipeline transforming unstructured audio into deeply hierarchical, structured study notes.
* 📈 **[event-driven-trading](https://github.com/angelazu-builder/event-driven-trading)**: Auditable event-driven US equities quantitative research engine with local analytical dashboards.
* 🚀 **[tech-launch-promoter-skill](https://github.com/angelazu-builder/tech-launch-promoter-skill)**: AI Agent Skill for generating developer launch threads, Show HN submissions, and 15-second screen demo scripts.

---

## ⚙️ Technical Capabilities & Stack

- **LLM Training Dynamics & Mechanics**: Context-length curricula, paired-seed experimental controls, preregistration protocols, BPC validation surfaces, Apple Silicon MPS profiling.
- **Quantitative Research & Econometrics**: Missing data theory (MCAR/MAR/MNAR), policy shock modeling, entity resolution (postcode-blocked Jaccard n-gram matching).
- **AI for Science & Stochastic Systems**: Kesten stochastic processes, active learning phase transition scans (GP+UCB), finite-size scaling, Hill MLE tail estimators.
- **AI & Agentic Systems**: OpenAI Responses API (`web_search` tool), Gemini Live API, Antigravity Agent Skills, AST import analysis pipelines.
- **Geospatial & Data Engineering**: Multi-source REST/Bulk ETL pipelines, Folium/Leaflet.js interactive geospatial visualization.
- **Languages & Frameworks**: Python (PyTorch, Numba, NumPy, SciPy, Pandas, Matplotlib), JavaScript / TypeScript, HTML/CSS, SQL.

---

## 📫 Connect & Portfolios

- 🎓 **Institution**: University of Oxford
- 🧠 **nanoGPT Research**: [angelazu-builder/nanoGPT](https://github.com/angelazu-builder/nanoGPT)
- 📊 **OSEP Research Portal**: [osep-quant-ai-social-impact](https://github.com/angelazu-builder/osep-quant-ai-social-impact)
- 🌌 **AI for Science Project**: [Datawhale_AI4S](https://github.com/angelazu-builder/Datawhale_AI4S)
- 🌐 **Interactive Maps**: [oxfordshire-population-map](https://angelazu-builder.github.io/oxfordshire-population-map/)
