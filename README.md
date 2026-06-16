<h1 align="center">Priyani</h1>

<p align="center">
  <b>Computer Science Engineering @ VIT Vellore</b> &nbsp;·&nbsp; Software Development &nbsp;·&nbsp; Applied Machine Learning
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/priyani-n/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

---

I build **end-to-end ML and full-stack systems** — from PyTorch forecasting models and NLP pipelines to the FastAPI services and React frontends that ship them. I do my best work under hackathon pressure: taking a real problem and turning it into a working, demoable product. Currently a CSE sophomore at VIT Vellore, focused on applied ML, backend systems, and software engineering.

---

### 🚀 Projects

#### [AarthiAI](https://github.com/PROSTLE/AarthiAI) — empathetic financial planner + stock forecaster
<sub>built at Women Techies</sub>

- **Forecasting** — PyTorch **bidirectional LSTM (3-layer, 128 hidden) with an attention head**; 60-day input window → 5-day price horizon. Adam + `ReduceLROnPlateau` + early stopping, trained per-ticker with leakage-safe scaling.
- **NLP sentiment** — **FinBERT + VADER** weighted ensemble (0.6 / 0.4) over financial news with a finance-tuned lexicon; a strong negative signal can override the technical forecast as a guardrail.
- **Serving** — FastAPI backend exposing prediction, sentiment, paper-trading, and an OpenEnv-style RL interface; Gemini for plain-language reasoning.

`PyTorch` · `Transformers / FinBERT` · `FastAPI` · `Gemini` · `yfinance`

#### [AEGIS](https://github.com/PROSTLE/AEGIS) — startup-terrain intelligence for India
<sub>built at Makeathon</sub>

- **9 independent intelligence modules** (survival, logistics, workforce, demand, investor matchmaking…) fused into a weighted **Launch Readiness Score**.
- **ML** — scikit-learn `GradientBoosting` survival model with an explainable per-factor breakdown.
- **Reliability** — Gemini advisor with a graceful fallback chain (`flash-lite → flash → rule-based`) so the live demo never fails.
- ~3.4k-LOC FastAPI backend · React 19 + D3.js + Zustand frontend (17 pages).

`React` · `FastAPI` · `scikit-learn` · `Gemini` · `D3.js`

#### [MGNREGA Demand Forecasting](https://github.com/aaditgarg01/ML_Hackathon) — 🥉 Neural Hack, 2nd Runner-Up
- District-level **time-series forecasting** of rural-employment demand (person-days & works) for Q1 2026.
- **Feature engineering** — 24-month lag features + district×calendar-month seasonal means + consistent cross-split label encoding.
- Dual `HistGradientBoostingRegressor` models with native missing-value handling.

`Python` · `pandas` · `scikit-learn`

---

### 🛠️ Skills

**Languages**
&nbsp;![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Machine Learning & Data**
&nbsp;![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)

**Backend & Web**
&nbsp;![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Tools**
&nbsp;![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white)

---

### 📌 Currently

- 🎓 CSE sophomore at **VIT Vellore** (B.Tech, 2025 – 2029)
- 🌱 Going deeper on **applied ML, system design, and backend engineering**
- 🤝 **Open to Software Engineering & ML internships** — [let's connect](https://www.linkedin.com/in/priyani-n/)
