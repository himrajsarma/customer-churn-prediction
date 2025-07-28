# 📊 Customer Churn Prediction using Machine Learning

This project aims to predict whether a customer will churn (i.e., leave a service provider) based on their demographic and usage behavior. The notebook is developed and run on [Kaggle](https://www.kaggle.com/) using the Telco Customer Churn dataset.

---

## 📌 Overview

- 🔍 Dataset: Telco Customer Churn  
- 📍 Platform: Kaggle Notebook (No local installations required)
- 🔧 ML Models: Logistic Regression, Random Forest, SVM, KNN
- 🎯 Goal: Identify patterns and build a predictive model for churn

---

## 🗂️ Dataset

- **Source**: [Telco Customer Churn - Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Rows**: 7,043
- **Target variable**: `Churn` (Yes/No)

---

## 🛠️ Tools & Libraries

All libraries used are pre-installed in Kaggle Notebooks:

- Python 3
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🔍 Steps Performed

### 📊 1. Exploratory Data Analysis (EDA)
- Uncovered patterns in churn by analyzing features like contract type, monthly charges, and tenure.
- Visualizations: bar plots, box plots, heatmaps

### 🧹 2. Data Preprocessing
- Converted `TotalCharges` to numeric
- Label encoded binary categories
- One-hot encoded multi-category variables
- Scaled numeric features with `StandardScaler`

### 🤖 3. Model Training
- Built and compared:
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
  - K-Nearest Neighbors (KNN)

### 📈 4. Evaluation
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- Feature Importance (via Random Forest)

---

## ✅ Key Insights

- Customers with **month-to-month contracts** and **high monthly charges** are more likely to churn.
- **Random Forest** performed the best with an accuracy close to 80%.
- `Contract`, `tenure`, and `MonthlyCharges` are the most influential features.

---

## 📎 Notebook Link

🔗 [View the Full Kaggle Notebook](https://www.kaggle.com/code/himrajsarma/customer-churn-prediction)

---

## 👨‍💻 Author

- **Himraj Sarma**
- GitHub: [@himrajsarma](https://github.com/himrajsarma)
- LinkedIn: [@himrajsarma](https://www.linkedin.com/in/himraj-sarma))
