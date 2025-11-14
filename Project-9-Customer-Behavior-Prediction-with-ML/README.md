# Project 09: Customer Behavior Prediction with ML 

## Project Overview

**Interconnect**, a telecom provider, is focused on improving customer loyalty by forecasting which users are at risk of churning. Anticipating churn allows the marketing team to offer proactive retention strategies like targeted promotions or customized plans.

This project focuses on:
- Exploring customer demographics, service usage, and contract features
- Identifying churn patterns and correlations
- Engineering features from usage logs and customer records
- Training classification models to predict churn probability
- Evaluating model performance using AUC-ROC and accuracy
- Supporting the marketing team with a reliable and interpretable tool

The final model will be used to flag high-risk customers and enable early outreach by the marketing department to reduce customer loss.

---

## 📦 Dataset Access

Due to file size limitations, the dataset is hosted externally on Google Drive.

### 🔽 Download Instructions

1. [**Click here to download the dataset from Google Drive**](https://drive.google.com/drive/folders/1mZ--ezkxjBE-0pGjKT-GLeorUL_QX6MI?usp=sharing)

2. Once downloaded, set up your project folder structure like this:

project-09-Predicting-Customer-Loss/ ├── interconnect_loss_prediction.ipynb └── datasets-to-upload/ ├── contract.csv ├── internet.csv├── personal.csv ├── phone.csv


---

> ⚠️ **Important:**  
> If the `datasets-to-upload` folder doesn't exist, create it manually and place the downloaded file inside.

---


## 🚀 Running the Notebook

1. Open `interconnect_loss_prediction.ipynb` using Jupyter Notebook or VS Code with a Jupyter extension.  
2. Make sure all 4 datasets are in the `datasets-to-upload/` folder.
3. Run all cells from top to bottom to reproduce the full analysis and model.

---

## 🧰 Tools & Technologies

- Python  
- Jupyter Notebooks  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- AUC-ROC, Accuracy