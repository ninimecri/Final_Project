FINAL PROJECT: PART 2. DS_Telecom
Made by Nicole Mejía.

# 📊 Customer Churn Analysis – Final Project

This project aims to explore and analyse customer behavior and contract data to identify key patterns that may influence service cancellation (churn) in a telecommunications company. It includes data preprocessing, exploratory analysis, correlation mapping, and dataset merging.

---

## 🧾 Project Files

- `Final project final version.ipynb`: Main Jupyter Notebook with data loading, cleaning, visualisation, and correlation analysis.
- `requirements.txt`: List of Python dependencies to run this project.
- `contract.csv`, `personal.csv`, `internet.csv`, `phone.csv` *(if included)*: Raw input datasets used for merging and analysis.

---

## 🧠 Objectives

- Merge and clean multiple customer datasets based on `customerID`.
- Identify patterns in features such as `MonthlyCharges`, `TotalCharges`, and contract status.
- Understand how customer demographics and services impact churn behavior.
- Visualize key insights using correlation heatmaps and plots.

---

## 🛠️ Technologies Used

- **Python 3.10+**
- `pandas`, `numpy` – Data handling and processing  
- `matplotlib`, `seaborn` – Visualizations  
- `scikit-learn` – Optional encoding and analysis tools

---

## 📌 Key Columns

- `customerID`: Unique identifier for each customer  
- `MonthlyCharges`, `TotalCharges`: Numeric indicators of spending  
- `SeniorCitizen`, `ContractActive`: Binary/categorical customer features  
- Other categorical features: `InternetService`, `OnlineSecurity`, etc.




