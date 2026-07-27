<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0d1117&height=160&section=header&text=Luca%20Neviani&fontSize=32&fontColor=f0f6fc&fontFamily=Inter&desc=Quantitative%20Data%20Scientist%20%26%20Applied%20Econometrician&descAlignY=66&descSize=15&descColor=58a6ff" width="100%"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=18&pause=1200&color=58A6FF&center=true&vCenter=true&width=650&lines=Econometrics,+Machine+Learning,+Data+Science;Geospatial+Data+Engineering+%26+Causal+Inference;Building+Autonomous+Multi-Agent+LLM+Systems;Audio+%26+NLP+Model+Fine-Tuning+(LoRA+%2F+PEFT)" alt="typing animation"/>
</p>

<p align="center">
  📍 <b>Padua, Italy</b> &nbsp;•&nbsp; 💼 <a href="https://linkedin.com/in/luca-neviani-97a146205"><b>LinkedIn</b></a> &nbsp;•&nbsp; 📧 <a href="mailto:lucaneviani01@gmail.com"><b>Email</b></a> &nbsp;•&nbsp; 🐙 <a href="https://github.com/lucaneviani"><b>GitHub</b></a>
</p>

---

I recently completed my **MSc in Applied Economics** (*Economic Data Analytics track*) at the **University of Padua**, with an exchange semester at the University of Cyprus. With a strong quantitative background in **econometrics and causal inference**, over the past year I have moved deeply into **machine learning, geospatial analytics, and AI systems development**—focusing on building end-to-end, production-ready pipelines rather than theoretical exercises.

I am currently looking for a **Junior Data Scientist / Quantitative Analyst** role where I can tackle complex data challenges, ship real-world models, and continuously learn on the job.

---

## 🔬 Featured Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### 🎙️ Google Waxal ASR <sub>(live)</sub>
**Qwen3-ASR 1.7B Fine-Tuning**

Fine-tuned **Qwen3-ASR (1.7B params)** for the Zindi Google Waxal Challenge, adapting a state-of-the-art speech model to transcribe three underrepresented African languages—Luganda, Shona, and Lingala—with very limited labeled data.

- Used **LoRA (PEFT)** to train only ~1.8% of the model's weights, cutting GPU memory needs by >80% versus full fine-tuning.
- Built an end-to-end audio/text preprocessing pipeline (16kHz resampling, transcript normalization) and evaluated via WER and CER.

<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LoRA_%2F_PEFT-8b5cf6?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Librosa-4051b5?style=flat-square" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/google-waxal-asr-challenge) &nbsp;|&nbsp; <sub>[Interactive Case Study →](https://lucaneviani.github.io/google-waxal-asr-challenge/)</sub>

</td>
<td width="50%" valign="top">

### 🌍 Causal Impact: Satellite Data <sub>(live)</sub>
**Renewable Energy Plants in Africa**

Designed and deployed an automated geospatial ETL pipeline combining NASA & ESA Earth observation imagery with RePP Africa georeferenced data to isolate the causal environmental and economic footprint of solar and wind power plants.

- Processed **259,480 panel observations** across 3,992 spatial units (2012–2024) using **Python & Google Earth Engine**.
- Applied **Callaway & Sant'Anna Doubly Robust Staggered DiD** in R, revealing divergent land cover impacts (solar barren expansion vs. wind landscape restoration).

<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Google%20Earth%20Engine-34A853?style=flat-square&logo=google&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=pandas&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Econometrics-8b93bf?style=flat-square" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/Geospatial-Analysis-of-Renewable-Energy-Power-Plants-using-Satellite-Data)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🤖 TradingAgents Plus <sub>(live)</sub>
**Autonomous Multi-Agent Trading System**

Extension of Tauric Research's open-source **TradingAgents** framework, transformed into a fully autonomous, production-grade trading pipeline with daily orchestration, portfolio tracking, real-time risk management, and automated broker execution.

<br><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LLM_Agents-6C63FF?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/SQLite-07405E?style=flat-square&logo=sqlite&logoColor=white" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/MultiAgent-Research-System)  
<sub>Builds on [TradingAgents](https://github.com/TauricResearch/TradingAgents) by Tauric Research</sub>

</td>
<td width="50%" valign="top">

### 📈 Numerai Crypto <sub>(live)</sub>
**LightGBM Tournament Model**

End-to-end machine learning pipeline for Numerai's Crypto quantitative tournament: feature engineering (momentum, volatility, RSI, cross-sectional rankings), a date-aware LightGBM regressor, and automated weekly predictions submitted via the Numerai API.

<br><br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LightGBM-4CAF50?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Numerai_API-1A1A2E?style=flat-square" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/Numerai-crypto-tournament-lightgbm-model)

</td>
</tr>
</table>

---

## 🛠️ Tech Stack & Competencies

| Category | Technologies & Tools |
|---|---|
| **Languages & Core** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **ML & Data Science** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-4CAF50?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Geospatial & Econometrics** | ![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-34A853?style=flat-square&logo=google&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-139C5A?style=flat-square&logo=pandas&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat-square&logo=qgis&logoColor=white) ![Causal Inference](https://img.shields.io/badge/Causal%20Inference-8b93bf?style=flat-square) |
| **Eng & Visualization** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat-square&logo=powerbi&logoColor=black) ![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white) |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucaneviani&layout=compact&theme=github_dark&hide_border=true&langs_count=6" height="160"/>
</p>
