# Demand Forecasting Project

Predict weekly sales for Walmart stores using **SARIMA** and **LSTM** models and provide actionable business insights for inventory, staffing, and promotions.

---

## 🔹 Project Overview

This project focuses on forecasting weekly sales using historical Walmart sales data. We use **time series analysis** and **deep learning** models to capture trends, seasonality, and complex patterns. The forecasts are then translated into business insights for inventory management, staffing, and marketing strategies.

---

## 🔹 Tech Stack

- **Languages:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, TensorFlow (Keras), Statsmodels  
- **Environment:** Jupyter Notebooks, VS Code  
- **Version Control:** Git & GitHub

---

## 🔹 Project Workflow

1. **Data Loading & Cleaning** (`00_data_loading.ipynb`)  
   - Load Walmart sales dataset  
   - Parse dates and clean missing data  

2. **Exploratory Data Analysis** (`01_eda_trend_seasonality.ipynb`)  
   - Visualize sales trends and seasonality  
   - Identify high and low demand periods  

3. **Stationarity & Decomposition** (`02_stationarity_decomposition.ipynb`)  
   - Check stationarity  
   - Decompose time series into trend, seasonality, and residuals  

4. **SARIMA Model** (`03_sarima_model.ipynb`)  
   - Train-test split  
   - SARIMA model fitting and forecasting  
   - Evaluation using RMSE and MAPE  
   - Save forecasts to `forecast_sarima.csv`  

5. **LSTM Model** (`04_lstm_model.ipynb`)  
   - Scale data using MinMaxScaler  
   - Train LSTM network for sales forecasting  
   - Evaluation and save forecasts to `forecast_lstm.csv`  

6. **Business Insights** (`05_business_insights.ipynb`)  
   - Compare SARIMA vs LSTM forecasts  
   - Provide actionable recommendations for:  
     - Inventory management  
     - Staffing allocation  
     - Promotions & marketing  
   - Evaluate forecast accuracy (RMSE & MAPE)  

---

## 🔹 Results

- **SARIMA Forecast RMSE:**  \`XX.XX\`  
- **SARIMA Forecast MAPE:** \`XX.XX%\`  
- **LSTM Forecast RMSE:**  \`XX.XX\`  
- **LSTM Forecast MAPE:** \`XX.XX%\`  

Visualizations show train vs actual vs forecast and highlight high-demand weeks.

---

## 🔹 Business Insights

- Increase stock during high-demand weeks (e.g., holidays)  
- Adjust staffing according to sales forecasts  
- Plan promotions during low-sales weeks  
- Use combined SARIMA + LSTM forecasts for robust decision-making  

---

## 🔹 Files in Repository

- `data/` – raw and processed datasets  
- `notebooks/` – Jupyter notebooks for each step  
- `venv/` – virtual environment  
- `README.md` – this file  

---

## 🔹 How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/bytebyanjalii/Demand-Forecasting-Project.git
   cd Demand-Forecasting-Project
