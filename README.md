# Momina Tariq
Software developer from Rawalpindi, Pakistan. I wanted to be a pilot growing up.
That did not happen, but the interest in aviation and aerospace never went away.
Finding out I could work on aviation problems through data engineering and ML was
what pulled me in this direction. Before pivoting I spent time building web 
applications and backends in JavaScript. The three projects below are where that pivot
landed.

---

## Projects

**[Flight-ETL-Pipeline](https://github.com/Momina0197/Flight-ETL-Pipeline)**  
ETL pipeline processing 13.7 million US domestic flight records from raw BTS
government CSVs into PostgreSQL. Generator-based chunked reader, multi-stage
cleaning, interactive query CLI. Carrier delays (5.14 min avg) outweigh weather
delays (0.82 min) across all 13.7M flights.

**[Jet-Engine-RUL](https://github.com/Momina0197/Jet-Engine-RUL)**  
Predictive maintenance system trained on NASA CMAPSS across all four sub-datasets.
Compared three classical models: Linear Regression, Random Forest, and XGBoost.
Random Forest achieved the lowest RMSE on all four sub-datasets, best result FD002
RMSE 17.45, R2 0.835. Rolling 5-cycle mean feature engineering per sensor per
engine. Classical models only. Sequential approaches like LSTM are a known gap.

**[Jet-Engine-RUL-api](https://github.com/Momina0197/Jet-Engine-RUL-api)**  
The RUL model deployed as a REST API with Streamlit frontend. Accepts 1-5 sensor
reading cycles, reconstructs rolling-mean features at inference using the exact
same pipeline as training. Models cut from 771MB to 97.8MB. Live predictions
validated against CMAPSS ground-truth RUL values.

---

## Technical Writing

* **Medium:** [What Three Classical Models Taught Me About Predicting Jet Engine Failure](https://medium.com/@mominatariq58/what-three-classical-models-taught-me-about-predicting-jet-engine-failure-865fef200279)  
  *An analysis evaluating classical feature-windowing models against published sequential deep learning baselines (Saxena et al., 2008; Heimes, 2008).*

---

## Stack
**Data & ML**: Python, Pandas, NumPy, scikit-learn, XGBoost, PostgreSQL, SQLAlchemy
**Deployment & Backend**: FastAPI, Streamlit, Docker, Docker Compose, REST APIs, Git
**Web & Legacy**: JavaScript, TypeScript, React, Node.js, Odoo 18

---

## Currently Learning

- Deep learning for time-series (LSTM, Transformers)
- MLflow for experiment tracking
- Airflow for pipeline orchestration

---

[LinkedIn](https://www.linkedin.com/in/momina-tariq-058262264)
