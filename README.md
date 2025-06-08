# -Telco-Customer-Churn-Prediction


## 📁 Project Description

This project focuses on predicting whether a customer will churn (i.e., leave a service provider) using classical machine learning models such as **Logistic Regression** and **Random Forest**. The dataset used is from a real-world telecom company and includes customer demographics, account details, and service usage patterns.

---

## 📌 Objective

Build, evaluate, and compare ML models to:

* Detect patterns in customer behavior
* Identify key drivers of churn
* Support business teams in retention strategies

---

## 🧰 Tools & Technologies

* **Python**
* **Pandas**, **NumPy**
* **Scikit-learn**
* **Matplotlib**, **Seaborn**
* Jupyter Notebook / Google Colab

---

## 📂 Dataset

**Source**: [Telco Customer Churn Dataset – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

* \~7,000 customer records
* Features: Demographics, tenure, service usage, billing info
* Target: `Churn` (Yes/No)

---

## ⚙️ Workflow

1. **Data Cleaning**

   * Removed `customerID`
   * Handled nulls in `TotalCharges`
2. **Feature Engineering**

   * Label encoded all categorical variables
3. **Modeling**

   * Trained **Logistic Regression**
   * Trained **Random Forest Classifier**
4. **Evaluation**

   * Accuracy, Precision, Recall, F1-Score
   * Confusion Matrix and Feature Importance analysis

---

## 📈 Results

| Model               | Accuracy | F1 Score (Churn) |
| ------------------- | -------- | ---------------- |
| Logistic Regression | \~80%    | \~0.65           |
| Random Forest       | \~82–84% | \~0.70–0.73      |

✅ Random Forest outperformed Logistic Regression in both precision and recall.

---

## 📊 Key Insights

* **Tenure**, **Contract Type**, and **Monthly Charges** were highly influential features.
* Customers with month-to-month contracts and high charges are more likely to churn.

---

## 🧪 Future Improvements

* Try SMOTE for class imbalance
* Use XGBoost or LightGBM for better performance
* Build a Streamlit dashboard for interactive churn prediction

---

## 🧑‍💻 Author

**Abdul Rahman** – AI/ML Intern
Want to add to this project or collaborate? [Let’s connect on LinkedIn](#)

---
