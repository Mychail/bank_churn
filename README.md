# 🏦 Bank Customer Churn Prediction

This project aims to predict whether a bank customer will churn (i.e., leave the bank) using supervised machine learning models. It includes full exploratory data analysis (EDA), feature engineering, model training, evaluation, and business recommendations.

---

## 📌 Objective

To build a predictive model that identifies customers at risk of churning, enabling the bank to take proactive steps to retain them.

---

## 📂 Dataset

- **Source:** Simulated bank dataset with 10,000 customer records.
- **Features:** Includes `CreditScore`, `Age`, `Gender`, `Tenure`, `Balance`, `NumOfProducts`, `IsActiveMember`, and more.
- **Target:** `Exited`  
  - `1` = Customer Churned  
  - `0` = Customer Retained

---

## 📊 Exploratory Data Analysis (EDA)

- Customers aged **35–65** showed higher churn rates.
- **Inactive members** are significantly more likely to churn.
- Customers with **only one product** had the highest churn.
- Female customers showed slightly higher churn tendencies.

---

## ⚙️ Preprocessing Steps

- Dropped uninformative columns (`RowNumber`, `CustomerID`, `Surname`)
- Encoded categorical features (`Gender`, `Geography`)
- Applied **StandardScaler** for feature scaling
- Addressed class imbalance using **SMOTE**

---

## 🤖 Models Evaluated

- Logistic Regression
- Linear Discriminant Analysis (LDA)
- Decision Tree
- Naive Bayes
- Support Vector Machine (SVM)

---

## 🧪 Model Evaluation

Metrics used:
- Accuracy
- Recall
- Precision
- F1-Score
- Confusion Matrix

> **SVM** and **Logistic Regression** had the best recall, making them ideal for identifying customers likely to churn.

---

## 💡 Business Recommendations

- Focus retention efforts on **older**, **inactive** customers.
- Promote **multi-product usage** through bundled offers.
- Engage customers with **zero balances** through targeted outreach.
- Track churn trends via **segment-level monitoring**.

---

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- SMOTE (Imbalanced-learn)
- Scikit-learn Pipelines

---

## 📁 Project Structure

