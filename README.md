# IBM Data Science Capstone Project

![Capstone banner](capstone/cover.png)

## Overview
This repository contains my capstone project and supporting labs from the IBM Data Science course.  
**Capstone focus:** [short 1-line summary of the problem — e.g., "Predicting SpaceX launch outcomes and building an interactive dashboard."]

## Contents
- `capstone/` — Final capstone deliverables (final notebook, DS-capstone-project.pdf, app)
- `labs/` — Course lab notebooks (EDA, SQL, web-scraping, etc.)
- `images/` — Plots and dashboard screenshots
- `requirements.txt` — Python dependencies
- `README.md` — (this file)

## Capstone Snapshot
**Key deliverables**
- Final report: `capstone/DS-capstone-project.pdf`
- Final notebook: `capstone/SpaceX_ML.ipynb`
- Interactive demo: **(add deployed URL here if available)**

**Top results**
- Best model: `XGBoost` — `R² = 0.XX`, `RMSE = XXXX`  
- Main insights: 1) … 2) … 3) …

![Predicted vs Actual](images/predicted_vs_actual.png)

## How to reproduce locally

```bash
git clone https://github.com/Rajarshi-ctrl/IBM-Data-Science-Capstone-Project.git
cd IBM-Data-Science-Capstone-Project
pip install -r requirements.txt
# open the final notebook
jupyter notebook capstone/SpaceX_ML.ipynb
# or run the Dash app
python capstone/spacex_dash_app.py
