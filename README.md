<div align="center">

# Luca Neviani
### In the making

<p align="center">
  <img src="https://img.shields.io/badge/Data%20Science%20%26%20Analytics-000000?style=for-the-badge&border=333333" />
  <img src="https://img.shields.io/badge/Machine%20Learning%20%26%20AI-000000?style=for-the-badge&border=333333" />
  <img src="https://img.shields.io/badge/Econometrics%20%26%20Causal%20Inference-000000?style=for-the-badge&border=333333" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/luca-neviani-97a146205"><img src="https://img.shields.io/badge/LinkedIn-000000?style=for-the-badge&logo=linkedin&logoColor=white&border=333333" /></a>
  <a href="mailto:lucaneviani01@gmail.com"><img src="https://img.shields.io/badge/Email-000000?style=for-the-badge&logo=gmail&logoColor=white&border=333333" /></a>
  <a href="https://github.com/lucaneviani"><img src="https://img.shields.io/badge/GitHub-000000?style=for-the-badge&logo=github&logoColor=white&border=333333" /></a>
  <img src="https://img.shields.io/badge/Padua%2C%20Italy-000000?style=for-the-badge&logo=googlemaps&logoColor=white&border=333333" />
</p>

</div>

---

MSc in **Economic Data Analytics** (*Applied Economics*), **University of Padua**.  
BSc in **Business Administration and Management**, **Ca' Foscari University of Venice**.

Quantitative background in economics, advanced econometrics, and causal inference. Over the past two years, my focus has shifted toward **Data Science, Machine Learning, and AI systems**, developing these skills through both academic work and personal projects, research, and real-world applications.

I mostly learn by doing, focusing on building and deploying end-to-end projects: I am passionate about researching and developing machine learning systems, ranging from LLM and speech model fine-tuning to autonomous agents, causal inference, and scalable data pipelines. 

My work focuses on understanding complex datasets, developing appropriate modeling approaches, and applying quantitative methods to extract meaningful insights and solve problems.

I am currently seeking a **Data Scientist / Business Analyst** role in a dynamic environment where I can tackle complex data challenges, ship real-world models, and continuously grow my technical skills on the job.


---

## My Projects

<table width="100%">
<tr>
<td width="50%" valign="top">

### Google Waxal ASR <sub>(live)</sub>
**Qwen3-ASR 1.7B Fine-Tuning**

Fine-tuned the open-source **Qwen3-ASR (1.7B params)** speech recognitioning model for the Zindi Google Waxal Challenge, adapting it to transcribe three underrepresented African languages: Luganda, Shona, and Lingala. 

- Applied LoRA, a fine-tuning technique, to update only a small subset of trainable parameters instead of retraining the entire model.
- Built an end-to-end audio processing pipeline including 16kHz resampling, audio normalization, and transcript preprocessing, preparing multilingual speech data for model training and evaluation.
- Improved ASR performance substantially, reducing Word Error Rate (WER) from 84.5% (zero-shot base model) to 18.2% after LoRA fine-tuning, and Character Error Rate (CER) from 68.0% to 6.4%.

<br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/PyTorch-111111?style=flat-square&logo=pytorch&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LoRA_%2F_PEFT-111111?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Librosa-111111?style=flat-square" height="20"/>


<br>

<p align="center">

<a href="https://github.com/lucaneviani/google-waxal-asr-challenge">
<img src="https://img.shields.io/badge/_Explore_Project-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://lucaneviani.github.io/google-waxal-asr-challenge/">
<img src="https://img.shields.io/badge/_View_The_Case_Study-2563EB?style=for-the-badge"/>
</a>

</p>

</td>
<td width="50%" valign="top">

### Causal Impact: Satellite Data <sub>(live)</sub>
**Renewable Energy Plants in Africa**

Research project developed in collaboration with the University of Padua, investigating the causal environmental and economic impact of solar and wind power plants in Africa. The study combines satellite-based remote sensing data with advanced econometric methods to isolate the causal effect.

- Built and processed a georeferenced panel dataset containing 259,480 observations using **Python and Google Earth Engine**.
- Collected, processed, and integrated large-scale remote sensing data from **NASA and ESA** satellite imagery through APIs.
- Applied advanced statistical and econometric techniques (Staggered DiD) using **Python and R**

<br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Google%20Earth%20Engine-111111?style=flat-square&logo=google&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/GeoPandas-111111?style=flat-square&logo=pandas&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/R-111111?style=flat-square&logo=r&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/Econometrics-111111?style=flat-square" height="20"/>

<br>

<p align="center">

<a href="https://github.com/lucaneviani/Geospatial-Analysis-of-Renewable-Energy-Power-Plants-using-Satellite-Data">
<img src="https://img.shields.io/badge/_Explore_Project-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### TradingAgents Plus <sub>(live)</sub>
**Autonomous Multi-Agent Trading System**

Extended Tauric Research's open-source TradingAgents framework, where specialized LLM-powered agents collaborate to perform investment research, analyze financial markets, debate alternative strategies, assess risk, and produce investment decisions.
- Enhanced the framework with a fully autonomous execution pipeline, including scheduled daily analyses, portfolio tracking, real-time risk monitoring, and automated broker execution.
- Integrated multiple specialized AI agents for fundamental, technical, and sentiment analysis.
- Designed a modular architecture enabling continuous portfolio management and end-to-end automation, from market research to trade execution.

<br><br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LLM_Agents-111111?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Docker-111111?style=flat-square&logo=docker&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/SQLite-111111?style=flat-square&logo=sqlite&logoColor=white" height="20"/>

<br>

<p align="center">

<a href="https://github.com/lucaneviani/MultiAgent-Research-System">
<img src="https://img.shields.io/badge/_Explore_Project-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

<p align="center">
<sub>Built on <a href="https://github.com/TauricResearch/TradingAgents">TradingAgents</a> by Tauric Research</sub>
</p>

</td>
<td width="50%" valign="top">

### Numerai Data Science Competition <sub>(live)</sub>
**Quantitative ML Tournament Model**

Participated in Numerai, a global data science tournament where participants build machine learning models to generate predictive signals for financial markets. 

- Developed an ensemble of LightGBM and XGBoost gradient boosting models optimized for large-scale tabular datasets, for financial time-series prediction.
- Engineered predictive features by applying feature analysis, regularization techniques, and systematic feature selection 
- Implemented walk-forward cross-validation to simulate real-world forecasting conditions and prevent temporal data leakage.
- Achieved top-10 ranked model submission among more than 13,000 competing models.


<br><br>
<img src="https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white" height="20"/> <img src="https://img.shields.io/badge/LightGBM-111111?style=flat-square" height="20"/> <img src="https://img.shields.io/badge/Numerai_API-111111?style=flat-square" height="20"/>

<br>

<p align="center">

<a href="https://github.com/lucaneviani/Numerai-crypto-tournament-lightgbm-model">
<img src="https://img.shields.io/badge/_Explore_Project-181717?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</p>

</td>
</tr>
</table>

---
### Technical Methodology

```mermaid
flowchart LR
    A["Data Processing & Feature Engineering<br><i>Spatial Panel Data, Time-Series, Audio Preprocessing, APIs</i>"] --> B["Algorithmic Modeling & Causal Inference<br><i>Econometrics, LightGBM, PEFT / LoRA, Multi-Agent Systems</i>"]
    B --> C["Evaluation & Production Deployment<br><i>Statistical Inference, Backtesting, FastAPI, Docker /i>"]
```

## Tech Stack & Competencies

| Category | Technologies & Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-111111?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-111111?style=flat-square&logo=r&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-111111?style=flat-square&logo=mysql&logoColor=white) |
| **ML & Data Science** | ![PyTorch](https://img.shields.io/badge/PyTorch-111111?style=flat-square&logo=pytorch&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-111111?style=flat-square&logo=scikitlearn&logoColor=white) ![LightGBM](https://img.shields.io/badge/LightGBM-111111?style=flat-square) ![Pandas](https://img.shields.io/badge/Pandas-111111?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-111111?style=flat-square&logo=numpy&logoColor=white) |
| **Geospatial & Econometrics** | ![Google Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-111111?style=flat-square&logo=google&logoColor=white) ![GeoPandas](https://img.shields.io/badge/GeoPandas-111111?style=flat-square&logo=pandas&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-111111?style=flat-square&logo=qgis&logoColor=white) ![Causal Inference](https://img.shields.io/badge/Causal%20Inference-111111?style=flat-square) |
| **Eng & Visualization** | ![Docker](https://img.shields.io/badge/Docker-111111?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-111111?style=flat-square&logo=git&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=flat-square&logo=fastapi&logoColor=white) ![Power BI](https://img.shields.io/badge/Power%20BI-111111?style=flat-square&logo=powerbi&logoColor=white) ![Plotly](https://img.shields.io/badge/Plotly-111111?style=flat-square&logo=plotly&logoColor=white) |

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=lucaneviani&show_icons=true&theme=github_dark&hide_border=true&count_private=true" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucaneviani&layout=compact&theme=github_dark&hide_border=true&langs_count=6" height="150"/>
</p>
