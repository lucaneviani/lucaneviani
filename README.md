<p align="center">
  <img src="assets/banner.svg" alt="Luca Neviani — Data Scientist in the making" width="100%"/>
</p>

<p align="center">
Padua, Italy · <a href="https://linkedin.com/in/luca-neviani-97a146205">LinkedIn</a> · <a href="mailto:lucaneviani01@gmail.com">Email</a> · <a href="https://github.com/lucaneviani">GitHub</a>
</p>

---

I'm finishing an MSc in Applied Economics (Economic Data Analytics track) at the University of Padua, with a semester at the University of Cyprus. My background is in econometrics and causal inference, but over the past year I've moved deeper into machine learning — mostly by building things rather than just reading about them: an autonomous trading system on top of an open-source LLM-agent framework, a Kaggle-trained model for Numerai, and a fine-tuned speech recognition model for children's voices.

I'm currently looking for a **Junior Data Scientist / Data Analyst** role where I can keep learning on the job.

---

## Projects

**TradingAgents Plus — Autonomous Multi-Agent Trading System**
An extension of Tauric Research's open-source **TradingAgents** framework — originally an interactive multi-agent LLM tool — turned into a fully autonomous, production-style pipeline.
- Built a daily orchestration layer: scheduling, candidate screening, and market-regime detection driving trade decisions
- Added portfolio tracking (SQLite) and real-time risk management (stop-loss/take-profit, exposure limits), integrated with Alpaca for paper/live execution, containerized with Docker

Tech: Python, LLM agents, Alpaca API, SQLite, Docker
→ [github.com/lucaneviani/MultiAgent-Research-System](https://github.com/lucaneviani/MultiAgent-Research-System)
*(builds on [TradingAgents](https://github.com/TauricResearch/TradingAgents) by Tauric Research — credited in the repo)*

**Numerai Crypto — LightGBM Tournament Model**
A complete ML pipeline for Numerai's Crypto tournament, from feature engineering to automated weekly submissions.
- Engineered momentum/volatility ratios, RSI-based features, and cross-sectional market-neutral rankings
- Trained a LightGBM regressor with date-aware validation and automated weekly submissions via the Numerai API

Tech: Python, LightGBM, Numerai API
→ [github.com/lucaneviani/Numerai-crypto-tournament-lightgbm-model](https://github.com/lucaneviani/Numerai-crypto-tournament-lightgbm-model)

**Whisper Fine-Tuning for Children's Speech Recognition**
Fine-tuned OpenAI's open-source Whisper model on children's speech (ages 4–11) — the base model, trained mostly on adult voices, performs poorly on noisy, high-pitched child speech.
- Trained and evaluated on Kaggle
- Reduced Word Error Rate from **[prima]% to [dopo]%** *(numeri da aggiungere)*

Tech: Python, PyTorch, Hugging Face Transformers
*(repo in preparazione — link in arrivo)*

**Causal Impact of Renewable Energy Plants in Africa — Satellite Data**
Expanded a georeferenced economic dataset with NASA/ESA satellite data via APIs, then used econometric methods to isolate the causal effect of renewable energy infrastructure on local economic indicators.

Tech: Python, QGIS, Econometrics
*(repo in preparazione — link in arrivo)*

---

## Tech Stack

**Languages** — Python, SQL
**Data Science & ML** — Pandas, NumPy, scikit-learn, PyTorch, Hugging Face Transformers
**Visualization** — Power BI, Plotly, Seaborn
**Tools** — Git, Docker, FastAPI, SQLite, Kaggle, LaTeX, VS Code

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=lucaneviani&layout=compact&theme=default&hide_border=true&langs_count=6" height="150"/>
</p>
