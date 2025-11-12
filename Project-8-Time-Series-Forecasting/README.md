# Project 08: Hourly Taxi Demand Forecasting

## Project Overview

**Sweet Lift Taxi**, a transportation company, collected historical data on taxi orders from airport locations. The goal is to build a time series model to predict the number of taxi orders for the upcoming hour allowing them to better allocate drivers during peak times.

This project focuses on:
- Analyzing patterns in hourly demand for taxis
- Extracting time-based features (hour, day of the week, lag values, rolling means)
- Using time series-aware train-validation splitting
- Training multiple regression models to minimize RMSE
- Tuning model parameters to ensure RMSE ≤ 48 on the test set
- Identifying the best model for real-time deployment

---

## 📦 Dataset Access

Due to file size limitations, the dataset is hosted externally on Google Drive.

### 🔽 Download Instructions

1. [**Click here to download the dataset from Google Drive**](https://drive.google.com/drive/folders/1mZ--ezkxjBE-0pGjKT-GLeorUL_QX6MI?usp=sharing)

2. Once downloaded, set up your project folder structure like this:

project-08-Time-Series-Forecasting/ ├── taxi-demand-forcasting.ipynb └── datasets-to-upload/ ├── taxi.csv

> ⚠️ **Important:**  
> If the `datasets-to-upload` folder doesn't exist, create it manually and place the downloaded file inside.

---

## 🚀 Running the Notebook

1. Open `taxi_demand_forecasting.ipynb` using Jupyter Notebook or VS Code with a Jupyter extension.  
2. Ensure the dataset file `taxi_orders.csv` is located in the same directory.  
3. Run all cells in order to reproduce the results and model evaluation.

---

## 🧰 Tools & Technologies

- Python  
- Jupyter Notebooks  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn   
- TimeSeriesSplit (for validation)