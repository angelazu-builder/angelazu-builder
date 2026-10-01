# Hi there, I'm Angela Zu! 👋

[![University of Oxford](https://img.shields.io/badge/University_of_Oxford-Laidlaw_Scholar-002147.svg?style=flat&logo=university-of-oxford&logoColor=white)](https://www.ox.ac.uk/)
[![AI for Science](https://img.shields.io/badge/Focus-AI_for_Science_%26_Econophysics-8A2BE2.svg)](#)
[![Python](https://img.shields.io/badge/Python-3.10+-3776AB.svg?logo=python&logoColor=white)](https://www.python.org/)
[![LLM Agent Systems](https://img.shields.io/badge/AI_Agents-Antigravity_%26_Gemini-FF6F00.svg)](#)

> 🎓 **Laidlaw Scholar & Researcher at the University of Oxford**  
> 🔬 **Research Focus**: AI for Science (AI4S) · Econophysics & Stochastic Dynamics · Active Learning & Agentic Systems · Quantitative Social Economy

---

## 🌟 Selected Research & Engineering Systems

### 🌌 [1. Candidate Phase Transitions in Wealth Inequality (AI for Science)](https://github.com/angelazu-builder/Datawhale_AI4S)
`Python` · `Numba JIT` · `Kesten Stochastic Dynamics` · `Active Learning (UCB+GP)` · `World Bank API Calibration`
* **Research Problem**: Identifying non-continuous candidate phase transition thresholds in high-dimensional Kesten wealth dynamics ($W_{t+1} = A_t \cdot W_t + B_t$) without high-dimensional grid search bottlenecks.
* **Key Innovations**:
  - Implemented a Numba JIT-accelerated simulator ($N=100,000$, $T=500$) with **Active Learning Agents (UCB + Gaussian Process Surrogate)** to discover candidate phase transitions at $R^* = p/c \approx 0.15 \sim 0.20$.
  - Conducted **Finite-Size Scaling ($N \in [5k, 100k]$)** convergence proofs, Hill/Newman MLE tail fitting, and Bootstrap 95% Confidence Intervals.
  - Discovered two emergent phenomena: **Absorbing Boundary Structural Collapse** ($R^2 < 0.50$) and **Keynesian MPC Power-Law Breakdown** ($c(W) \sim W^{-\alpha}$).
  - Calibrated parameters with World Bank API macro data for US and China historical Gini coefficients.
* 🔗 [Repository](https://github.com/angelazu-builder/Datawhale_AI4S) | 📄 [Research Report (PDF/Docx)](https://github.com/angelazu-builder/Datawhale_AI4S/blob/main/docs/submission/03_%E5%AE%8C%E6%95%B4%E7%A0%94%E7%A9%B6%E6%8A%A5%E5%91%8A_Final_Report_v1.1.0.md) | 🌐 [English Readme](https://github.com/angelazu-builder/Datawhale_AI4S/blob/main/README_EN.md)

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

### 🤖 [3. Gemini Live Multimodal AI Tutor](https://github.com/angelazu-builder/gemini-live-multimodal-tutor)
`JavaScript` · `Gemini Live API` · `Multimodal Audio & Vision` · `Google Cloud Hackathon 2026`
* **Problem**: Traditional e-learning interfaces lack conversational adaptation and real-time visual problem-solving feedback.
* **What I Built**: Built for **Google Cloud Hackathon 2026**, an interactive multimodal AI cognitive companion leveraging the **Gemini Live API** for real-time voice and visual interaction during complex problem solving.
* 🔗 [Repository](https://github.com/angelazu-builder/gemini-live-multimodal-tutor)

---

### 📝 [4. CrystalNotes — AI Transcript Intelligence](https://github.com/angelazu-builder/CrystalNotes)
`TypeScript` · `LLM Systems` · `NLP` · `Productivity Engineering`
* **Problem**: Unstructured audio transcripts are time-consuming to review and lack clear hierarchical structure.
* **What I Built**: An AI-powered transcript processor that extracts core insights and formats them into deeply-layered, structured bullet notes.
* 🔗 [Repository](https://github.com/angelazu-builder/CrystalNotes)

---

### 🗺️ [5. Oxfordshire Population Density & Settlement Map Portal](https://github.com/angelazu-builder/oxfordshire-population-map)
`Python` · `Folium / Leaflet.js` · `Geospatial Data Science` · `Spatial Modeling`
* **Problem**: Communicating spatial variations in population density and social enterprise distribution across UK census postcodes (`OX1`–`OX49`).
* **What I Built**: Standalone interactive spatial mapping portal featuring choropleth layers, income quintile circle markers, and ward boundary tooltips.
* 🔗 [Repository](https://github.com/angelazu-builder/oxfordshire-population-map) | 🌐 [Live Map Portal](https://angelazu-builder.github.io/oxfordshire-population-map/)

---

## 🛠️ Research & Technical Capabilities

- **AI for Science & Econophysics**: Kesten Stochastic Processes, Candidate Phase Transition Scans, Active Learning (GP+UCB), Finite-Size Scaling, Hill MLE Estimators.
- **Quantitative Research & Econometrics**: Missing Data Theory (MCAR/MAR/MNAR), Structural Selection, Elasticity Modeling, Policy Shock Econometrics.
- **AI & Agentic Systems**: OpenAI Responses API (`web_search` tool), Gemini Live API, Structured JSON Outputs, Antigravity Agent Skills.
- **Geospatial & Data Engineering**: Multi-Source REST/Bulk ETL Pipelines, Postcode Blocking Fuzzy Matchers, Folium/Leaflet.js Spatial Analytics.
- **Languages & Frameworks**: Python (Numba, NumPy, SciPy, Pandas, Matplotlib), JavaScript/TypeScript, HTML/CSS, SQL.

---

## 📫 Connect & Portfolios

- 🎓 **Institution**: University of Oxford
- 🌐 **Interactive Maps**: [oxfordshire-population-map](https://angelazu-builder.github.io/oxfordshire-population-map/)
- 📊 **OSEP Research Portal**: [osep-quant-ai-social-impact](https://github.com/angelazu-builder/osep-quant-ai-social-impact)
- 🌌 **AI for Science Project**: [Datawhale_AI4S](https://github.com/angelazu-builder/Datawhale_AI4S)
