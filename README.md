<div align="center">

# Luca Neviani
### Data Science • Machine Learning • Econometrics

<p align="center">
  <img src="https://img.shields.io/badge/▪%20Core%20Focus-Data%20Science%20%26%20Analytics-000000?style=for-the-badge&border=333333" />
  <img src="https://img.shields.io/badge/▪%20Core%20Focus-Machine%20Learning%20%26%20AI-000000?style=for-the-badge&border=333333" />
  <img src="https://img.shields.io/badge/▪%20Core%20Focus-Econometrics%20%26%20Causal%20Inference-000000?style=for-the-badge&border=333333" />
</p>

<p align="center">
  ▪ <b>Padua, Italy</b> &nbsp;•&nbsp; ▪ <a href="https://linkedin.com/in/luca-neviani-97a146205"><b>LinkedIn</b></a> &nbsp;•&nbsp; ▪ <a href="mailto:lucaneviani01@gmail.com"><b>Email</b></a> &nbsp;•&nbsp; ▪ <a href="https://github.com/lucaneviani"><b>GitHub</b></a>
</p>

</div>

---

MSc in **Economic Data Analytics** (*Applied Economics*), **University of Padua**.  
Quantitative background in economics, advanced econometrics, and causal inference. Over the past two years, my focus has shifted toward **Data Science, Machine Learning, and AI systems**.

I am a strong believer in learning by doing, focusing on building and deploying hands-on, end-to-end projects—from autonomous multi-agent systems and ML tournament regressors to geospatial data pipelines and LLM fine-tuning.

I am currently seeking a **Junior Data Scientist / Data Analyst** role in a dynamic environment where I can tackle complex data challenges, ship real-world models, and continuously grow my technical skills on the job.

---

## // My Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### ▪ Google Waxal ASR <sub>(live)</sub>
**Qwen3-ASR 1.7B Fine-Tuning**

Fine-tuned **Qwen3-ASR (1.7B params)** for the Zindi Google Waxal Challenge, adapting a state-of-the-art speech model to transcribe three underrepresented African languages—Luganda, Shona, and Lingala—with very limited labeled data.

- Used **LoRA (PEFT)** to train only ~1.8% of the model's weights, cutting GPU memory needs by >80% versus full fine-tuning.
- Built an end-to-end audio/text preprocessing pipeline (16kHz resampling, transcript normalization) and evaluated via WER and CER.

<br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/PyTorch-111111?style=flat-square&logo=pytorch&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LoRA_%2F_PEFT-111111?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Librosa-111111?style=flat-square" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/google-waxal-asr-challenge) &nbsp;|&nbsp; <sub>[Interactive Case Study →](https://lucaneviani.github.io/google-waxal-asr-challenge/)</sub>

</td>
<td width="50%" valign="top">

### ▪ Causal Impact: Satellite Data <sub>(live)</sub>
**Renewable Energy Plants in Africa**

Designed and deployed an automated geospatial ETL pipeline combining NASA & ESA Earth observation imagery with RePP Africa georeferenced data to isolate the causal environmental and economic footprint of solar and wind power plants.

- Processed **259,480 panel observations** across 3,992 spatial units (2012–2024) using **Python & Google Earth Engine**.
- Applied **Callaway & Sant'Anna Doubly Robust Staggered DiD** in R, revealing divergent land cover impacts (solar barren expansion vs. wind landscape restoration).

<br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Google%20Earth%20Engine-111111?style=flat-square&logo=google&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/GeoPandas-111111?style=flat-square&logo=pandas&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/R-111111?style=flat-square&logo=r&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Econometrics-111111?style=flat-square" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/Geospatial-Analysis-of-Renewable-Energy-Power-Plants-using-Satellite-Data)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### ▪ TradingAgents Plus <sub>(live)</sub>
**Autonomous Multi-Agent Trading System**

Extension of Tauric Research's open-source **TradingAgents** framework, transformed into a fully autonomous, production-grade trading pipeline with daily orchestration, portfolio tracking, real-time risk management, and automated broker execution.

<br><br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LLM_Agents-111111?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Docker-111111?style=flat-square&logo=docker&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/SQLite-111111?style=flat-square&logo=sqlite&logoColor=white" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/MultiAgent-Research-System)  
<sub>Builds on [TradingAgents](https://github.com/TauricResearch/TradingAgents) by Tauric Research</sub>

</td>
<td width="50%" valign="top">

### ▪ Numerai Crypto <sub>(live)</sub>
**LightGBM Tournament Model**

End-to-end machine learning pipeline for Numerai's Crypto quantitative tournament: feature engineering (momentum, volatility, RSI, cross-sectional rankings), a date-aware LightGBM regressor, and automated weekly predictions submitted via the Numerai API.

<br><br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LightGBM-111111?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Numerai_API-111111?style=flat-square" height="20"/>

<br><br>
[**View Repository →**](https://github.com/lucaneviani/Numerai-crypto-tournament-lightgbm-model)

</td>
</tr>
</table>

---

## // Tech Stack & Competencies

| Category | Technologies & Tools |
|---|---|
| **Languages & Core** | ![Python](https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-111111?style=flat-square&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-111111?style=flat-square&logo=mysql&logoColor=white) |
| **ML & Data Science** | ![PyTorch](https://img.shields.io/badge/PyTorch-111111?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-111111?style=flat-square&logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-111111?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-111111?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-111111?style=flat-square&logo=numpy&logoColor=white) |
| **Geospatial & Econometrics** | ![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-111111?style=flat-square&logo=google&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-111111?style=flat-square&logo=pandas&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-111111?style=flat-square&logo=qgis&logoColor=white) ![Causal Inference](https://img.shields.io/badge/Causal%20Inference-111111?style=flat-square) |
| **Eng & Visualization** | ![Docker](https://img.shields.io/badge/Docker-111111?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-111111?style=flat-square&logo=git&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=flat-square&logo=fastapi&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-111111?style=flat-square&logo=powerbi&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-111111?style=flat-square&logo=plotly&logoColor=white) |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucaneviani&layout=compact&bg_color=0D1117&title_color=ffffff&text_color=cccccc&icon_color=ffffff&border_color=333333&hide_border=false&langs_count=6" height="160"/>
</p>
