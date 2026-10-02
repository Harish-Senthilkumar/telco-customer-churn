# Telecom Customer Churn Prediction 📡

A Machine Learning project focused on analyzing telecom customer retention, evaluating key behavioral drivers, and predicting churn using Decision Trees and Random Forest Classifiers.

---

## 📌 Project Overview
Customer attrition impacts revenue in subscription-based telecom models. This project establishes an end-to-end data pipeline to preprocess customer behavioral metrics, encode categorical variables, and train ensemble classification models to accurately forecast churn risk.

---

## 🛠️ Tech Stack & Libraries
* **Language:** Python 3.14
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (`DecisionTreeClassifier`, `RandomForestClassifier`, `train_test_split`, `metrics`)

---

## 📂 Repository Structure
├── data/
│   └── telecom_data.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── LICENSE
└── README.md

---

## 🚀 Quickstart Guide

### 1. Clone the Repository
```bash
git clone [https://github.com/Harish-Senthilkumar/telecom-customer-churn.git](https://github.com/Harish-Senthilkumar/telecom-customer-churn.git)
cd telecom-customer-churn

### 2. Set Up Virtual Environment & Install Dependencies

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

### 3. Launch Notebook
jupyter notebook notebooks/churn_analysis.ipynb