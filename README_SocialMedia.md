# Social Media Addiction Risk Modeling & Analytical Dashboard

![Python](https://img.shields.io/badge/Python-3.x-blue) ![Tableau](https://img.shields.io/badge/Tableau-Dashboard-orange) ![ML](https://img.shields.io/badge/ML-KNN%20%7C%20Softmax-green) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

## Overview
An end-to-end machine learning and business intelligence project that predicts social media addiction risk levels for users and translates the results into an interactive 5-dashboard Tableau solution. The project covers the full analytics lifecycle — from raw data and feature engineering through to executive-level visual insights.

## Problem Statement
Social media overuse is a growing concern impacting mental health, sleep, and academic performance. This project aims to quantify addiction risk using behavioral data and machine learning, and communicate findings through actionable BI dashboards.

## Dataset
- **Source:** Kaggle
- **Features:** Social media usage patterns, sleep hours, mental health indicators, academic performance metrics, platform usage, age groups, and geographic data

## Project Workflow
```
Raw Data → Exploratory Data Analysis → Feature Engineering → ML Modeling → Risk Index → Tableau Dashboards
```

## Machine Learning Models
| Model | Purpose |
|-------|---------|
| K-Nearest Neighbors (KNN) | Addiction score classification |
| Softmax Regression | Multi-class risk prediction |

## Addiction Risk Index
A composite score combining ML model output with behavioral features:
- **Low Risk** — Minimal signs of problematic usage, healthy sleep and academics
- **Moderate Risk** — Elevated usage with mild behavioral impact
- **High Risk** — Heavy usage with significant mental health and academic deterioration

## Feature Engineering
Features engineered across 4 data domains:
- 📱 **Usage** — Daily screen time, sessions per day, platform preferences
- 😴 **Sleep** — Average sleep hours, sleep disruption patterns
- 🧠 **Mental Health** — Self-reported wellbeing scores, stress indicators
- 🎓 **Academic** — GPA impact, study hours, distraction frequency

## Tableau Dashboards
5 interactive dashboards built for comprehensive risk analysis:
1. **Addiction Overview** — Overall risk distribution and severity KPIs
2. **Platform Analysis** — High-risk platforms identification
3. **Demographic Analysis** — Risk breakdown by age group
4. **Geographic Analysis** — Risk patterns across geographies
5. **Lifestyle Impact** — Sleep, mental health, and academic correlations

## Key Findings
- Identified high-risk platforms, age groups, and geographies through visualization
- Segmented users into 3 risk tiers enabling targeted intervention strategies
- Translated ML outputs into business-focused insights accessible to non-technical stakeholders

## Tech Stack
| Tool | Usage |
|------|-------|
| Python (Pandas, NumPy) | Data cleaning & feature engineering |
| Scikit-learn | KNN & Softmax model building |
| Tableau | Dashboard development |
| Jupyter Notebook | EDA & model development |

## Repository Structure
```
├── data/
│   └── social_media_dataset.csv
├── notebooks/
│   └── addiction_risk_modeling.ipynb
├── dashboards/
│   └── addiction_dashboard.twbx
├── images/
│   └── dashboard_screenshots/
└── README.md
```

## How to Run
1. Clone the repository
```bash
git clone https://github.com/yourusername/social-media-addiction-risk
```
2. Install dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```
3. Open the notebook
```bash
jupyter notebook notebooks/addiction_risk_modeling.ipynb
```
4. Open `dashboards/addiction_dashboard.twbx` in Tableau Desktop or Tableau Public

## Author
**Hrishikesh Umesh Dixit**
MS Information Systems — University of Texas at Arlington
[LinkedIn](https://linkedin.com/in/hrishikesh-dixit) · [Portfolio](https://yourportfolio.com)
