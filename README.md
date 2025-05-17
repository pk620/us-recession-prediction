# 🧠 U.S. Recession Prediction Using Economic Indicators

This project analyzes and models U.S. recessions using macroeconomic indicators from the [FRED API](https://fred.stlouisfed.org/). It includes data visualization and a simple logistic regression model to explore the relationships between indicators and recession periods.

---

## 📊 Overview

Using data from 1970–2024, this project covers:

- Fetching and cleaning time-series data from FRED
- Visualizing key economic indicators:
  - Unemployment Rate
  - CPI (Inflation)
  - Federal Funds Rate
  - Yield Curve (10Y - 2Y Treasury Spread)
  - Consumer Sentiment (UMCSENT)
  - Industrial Production (INDPRO)
- Engineering a new feature: Yield Curve inversion
- Modeling recession probability with logistic regression
- Evaluating model performance with classification metrics

---

## 📈 Sample Visualizations

Each chart highlights the relationship between an indicator and historical U.S. recessions (shaded in red):

- **Unemployment Rate**  
  Increases significantly during recessions

- **Yield Curve**  
  Inversions (below 0) often precede recessions

- **CPI (Inflation)**  
  Helps contextualize economic trends

---

## 🔍 Model Summary

A logistic regression model was trained to estimate recession likelihood based on:

- Unemployment Rate  
- CPI  
- Fed Funds Rate  
- Yield Curve

**Top Predictor:** Yield Curve

The model demonstrates strong overall accuracy but struggles to predict rare recession events due to data imbalance — a known challenge in economic forecasting.

---

## 📌 Key Learnings

- Time-series analysis using real-world macroeconomic data
- Feature engineering (e.g., Yield Curve)
- Logistic regression modeling & interpretation
- Communicating insights with clear visualizations and summaries

---

## 🛠 Tools Used

- Python (Pandas, Matplotlib, Seaborn, Scikit-learn)
- Google Colab
- FRED API (via `pandas_datareader`)

---

## 📂 Files

- `recession_analysis.ipynb`: Full Colab notebook with visualizations and model
- `README.md`: Project summary

---

## 🤔 Future Improvements

- Explore more advanced models (e.g., time-series forecasting or ensemble methods)
- Address data imbalance using SMOTE or resampling
- Build an interactive dashboard

---

## 📬 Contact

Feel free to connect or reach out if you'd like to discuss this project or similar work!

