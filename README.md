# README.md

## Project: Sales Forecasting using Traditional + Machine Learning + Deep Learning Models

This project aims to forecast future sales using a variety of models ranging from statistical methods to advanced machine learning and deep learning approaches.  
It involves extensive **feature engineering**, **model comparison**, and **performance evaluation**.

---

## Features

- **Data Preprocessing & Cleaning**
- **Feature Engineering**  
  - Calendar-based features
  - Lag features
  - Rolling mean features
- **Modeling Techniques**  
  - Naive Baseline
  - ARIMA
  - Random Forest Regressor
  - XGBoost Regressor
  - Prophet
  - LSTM
- **Evaluation Metrics**  
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
- **Visualization**  
  - Actual vs Predicted comparison for each model

---

## Folder Structure

```bash
├── Wiseanalytics.ipynb        # Main analysis notebook
├── README.md                   # Project Documentation
└── images/                     # Plots and result images
```

---

## Models and Libraries Used

- `pandas`, `numpy`
- `scikit-learn`
- `xgboost`
- `prophet`
- `statsmodels`
- `keras` (for LSTM)
- `matplotlib`, `seaborn`

---

## How to Run

1. Download the ipynb file.
2. Install dependencies:
   ```bash
   pip install pandas numpy scikit-learn xgboost prophet statsmodels keras matplotlib seaborn
   ```
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Wiseanalytics.ipynb
   ```
4. Run cells step-by-step to train and evaluate models.

---

## Evaluation

- The models were compared based on **Error Rate**, **RMSE**, and **MAE**.
- Final visualization shows how close each model's prediction is to the actual sales values.

---

## Key Insights

- Feature engineering plays a critical role in improving model performance.
- Ensemble methods like **Random Forest** and **XGBoost** performed better than traditional time series models like **ARIMA** on the given dataset.
- **LSTM** models benefit from sequential data but need careful tuning and more data for best performance.

> **_"The goal is not to predict the future perfectly, but to make fewer mistakes."_**
