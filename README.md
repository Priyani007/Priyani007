<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FFC2D1,50:FF9EB8,100:FB6F92&height=170&section=header&text=&fontSize=0" alt="" />

<h1 align="center">Hey, I'm Priyani 🌸</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/priyani-n/">
    <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=22&duration=3200&pause=900&color=FB6F92&center=true&vCenter=true&width=640&height=46&lines=Computer+Science+Engineer+%40+VIT+Vellore;I+build+end-to-end+ML+%2B+full-stack+systems;Open+to+SWE+%26+ML+internships" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/priyani-n/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-FF6FA5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
</p>

<p align="center">
  I build <b>end-to-end ML and full-stack systems</b> — from PyTorch forecasting models and NLP pipelines<br/>
  to the FastAPI services and React frontends that ship them. I do my best work under hackathon pressure:<br/>
  taking a real problem and turning it into a working, demoable product.
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:FFC2D1,100:FB6F92&height=3" alt="" />

## 🚀 Projects

### 💸 [AarthiAI](https://github.com/PROSTLE/AarthiAI) — empathetic financial planner + stock forecaster
<sub>built at Women Techies</sub>

- **Forecasting** — PyTorch **bidirectional LSTM (3-layer, 128 hidden) with an attention head**; 60-day input window → 5-day price horizon. Adam + `ReduceLROnPlateau` + early stopping, trained per-ticker with leakage-safe scaling.
- **NLP sentiment** — **FinBERT + VADER** weighted ensemble (0.6 / 0.4) over financial news with a finance-tuned lexicon; a strong negative signal can override the technical forecast as a guardrail.
- **Serving** — FastAPI backend exposing prediction, sentiment, paper-trading, and an OpenEnv-style RL interface; Gemini for plain-language reasoning.

<sub>`PyTorch` · `Transformers / FinBERT` · `FastAPI` · `Gemini` · `yfinance`</sub>

### 🛰️ [AEGIS](https://github.com/PROSTLE/AEGIS) — startup-terrain intelligence for India
<sub>built at Makeathon</sub>

- **9 independent intelligence modules** (survival, logistics, workforce, demand, investor matchmaking…) fused into a weighted **Launch Readiness Score**.
- **ML** — scikit-learn `GradientBoosting` survival model with an explainable per-factor breakdown.
- **Reliability** — Gemini advisor with a graceful fallback chain (`flash-lite → flash → rule-based`) so the live demo never fails.
- ~3.4k-LOC FastAPI backend · React 19 + D3.js + Zustand frontend (17 pages).

<sub>`React` · `FastAPI` · `scikit-learn` · `Gemini` · `D3.js`</sub>

### 📊 [MGNREGA Demand Forecasting](https://github.com/aaditgarg01/ML_Hackathon) &nbsp;·&nbsp; 🥉 Neural Hack, 2nd Runner-Up
- District-level **time-series forecasting** of rural-employment demand (person-days & works) for Q1 2026.
- **Feature engineering** — 24-month lag features + district×calendar-month seasonal means + consistent cross-split label encoding.
- Dual `HistGradientBoostingRegressor` models with native missing-value handling.

<sub>`Python` · `pandas` · `scikit-learn`</sub>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:FFC2D1,100:FB6F92&height=3" alt="" />

## 🛠️ Skills

<table>
  <tr>
    <td><b>Languages</b></td>
    <td>
      <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
      <img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
    </td>
  </tr>
  <tr>
    <td><b>ML &amp; Data</b></td>
    <td>
      <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
      <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white" />
      <img src="https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black" />
      <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white" />
      <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Backend &amp; Web</b></td>
    <td>
      <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" />
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
    </td>
  </tr>
  <tr>
    <td><b>Tools</b></td>
    <td>
      <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
      <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
      <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white" />
      <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
    </td>
  </tr>
</table>

## 📌 Currently

- 🎓 CSE sophomore at **VIT Vellore** (B.Tech, 2025 – 2029)
- 🌱 Going deeper on **applied ML, system design, and backend engineering**
- 🤝 **Open to Software Engineering & ML internships** — [let's connect](https://www.linkedin.com/in/priyani-n/)

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:FB6F92,50:FF9EB8,100:FFC2D1&height=120&section=footer&text=&fontSize=0" alt="" />
