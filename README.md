# 🛒 E-Commerce Sales Analysis & Prediction

> **Predicting sales revenue from marketing metrics using end-to-end ML pipelines — XGBoost achieving ~91% R²**

[![Live Demo](https://img.shields.io/badge/🌐_Live_README-View_Interactive-00e5a0?style=for-the-badge)](https://yourusername.github.io/ecommerce-sales-prediction/README)
[![Notebook](https://img.shields.io/badge/📓_Notebook-Open-7c5cfc?style=for-the-badge)](./E-Commerce_Analysis___Prediction.ipynb)
[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![XGBoost](https://img.shields.io/badge/XGBoost-Winner-ff6b35?style=for-the-badge)](https://xgboost.readthedocs.io)
![Power BI Dashboard](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)

---

## 📌 Project Overview

An end-to-end machine learning project that analyses e-commerce marketing data and predicts **sales revenue** using regression models. The project covers the full data science lifecycle — from raw CSV ingestion to cross-validated predictions.

---

## 🚀 Results at a Glance

| Model | Train R² | Test R² | Notes |
|---|---|---|---|
| Linear Regression | ~0.72 | ~0.70 | Baseline — interpretable but limited |
| Random Forest | ~0.92 | ~0.78 | Overfits on training data |
| **XGBoost** ⭐ | **~0.95** | **~0.91** | **Best generalisation — selected model** |

> 5-fold cross-validation used to confirm model stability.

---

## 🧠 ML Pipeline

```
Data Ingestion → EDA → Cleaning & Imputation → Feature Engineering → Model Training → Cross-Validation → Predictions
```

---

## 📊 Features Used

**Numerical:** `ad_spend`, `price`, `discount_rate`, `market_reach`, `impressions`, `click_through_rate`, `competition_index`, `seasonality_index`, `campaign_duration_days`, `customer_lifetime_value`

**Categorical (OHE):** `region`, `channel`, `product_category`, `customer_segment`

---

## 🛠 Tech Stack

`Python` · `Pandas` · `NumPy` · `Scikit-learn` · `XGBoost` · `Matplotlib` · `Seaborn` · `Jupyter Notebook` · `Power BI`

---

## 🔍 Key Findings

- **Revenue is right-skewed** - a few high-value campaigns dominate the mean
- **Ad spend, impressions & market reach** show the strongest correlation with revenue
- **Channel type** significantly impacts both total and average revenue
- **Regional differences** in revenue are amplified or dampened by the marketing channel used

---

## 📁 Project Structure

```
├── E-Commerce Sales Analysis & Prediction.ipynb   # Main notebook
├── README.html                              # Interactive visual README
├── README.md                               # This file
├── train.csv                               # Training dataset
└── test.csv                                # Test dataset
```

---

## ▶️ How to Run

```bash
# Clone the repo
git clone https://github.com/Mayank312003/E-Commerce-Sales-Prediction.git
cd E-Commerce-Sales-Prediction

# Install dependencies
pip install pandas numpy scikit-learn xgboost matplotlib seaborn jupyter

# Launch notebook
jupyter notebook E-Commerce Sales Analysis & Prediction.ipynb
```

---

## 📊 Dashboard

<img width="1703" height="728" alt="ss" src="https://github.com/user-attachments/assets/e7e8009f-fabc-402b-ace3-5d2dfb6100a3" />

---
## 📬 Let's Connect

If you're a recruiter or hiring manager — feel free to check out the **[interactive README](https://Mayank312003.github.io/E-Commerce-Sales-Prediction/index)** for a visual walkthrough of this project.

> ⭐ Star this repo if you found it useful!
