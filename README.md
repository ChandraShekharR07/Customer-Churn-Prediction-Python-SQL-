# 📊 Customer Churn Prediction (Python + SQL)

A predictive analytics project using **SQL** for data transformation and **Python** for machine learning to identify customers likely to churn from a telecom company.  
Achieved an **83% accuracy** using a Random Forest Classifier and derived actionable insights for improving customer retention.

---

## 🔍 Introduction

Customer churn poses a major threat to telecom providers, impacting both revenue and growth. This project demonstrates how businesses can use data-driven solutions to anticipate and reduce customer churn by leveraging structured data and predictive modeling techniques.

---

## 🎯 Business Objective

- Predict which customers are likely to leave the telecom service.
- Understand key factors influencing churn such as **tenure**, **contract type**, and **payment method**.
- Support marketing and retention teams with actionable insights to reduce churn rates and improve loyalty.

---

## 🛠️ Tools & Technologies Used

| Category           | Tools / Libraries                             |
|-------------------|-----------------------------------------------|
| Language           | Python, SQL                                   |
| Data Handling      | pandas, numpy                                 |
| Visualization      | matplotlib, seaborn                           |
| SQL Integration    | pyodbc, SQLAlchemy, Microsoft SQL Server      |
| Machine Learning   | scikit-learn (Random Forest Classifier)       |
| Dataset Source     | [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) |
| Notebook Format    | Jupyter Notebook                              |

---

## 🧠 Problem Statement

Telecom companies struggle with high customer churn due to competitive pricing, low customer satisfaction, and poor service delivery. By analyzing customer behavior and account information, we aim to:

- Predict churn probability with machine learning.
- Highlight top features contributing to churn.
- Suggest actionable strategies to retain customers.

---

## 🔄 Project Workflow

1. **📥 Data Extraction (SQL):**
   - Queried customer data directly from a relational database using `pyodbc`.
   - Cleaned data at the source using SQL commands for efficiency.

2. **🧹 Data Cleaning & Preprocessing (Python):**
   - Converted `TotalCharges` to numeric, handled nulls, encoded categorical variables.
   - Feature selection and correlation analysis using heatmaps.

3. **📊 Exploratory Data Analysis (EDA):**
   - Visualized churn by contract type, gender, tenure, and monthly charges.
   - Identified patterns correlating with churn behavior.

4. **🧠 Model Training:**
   - Built a **Random Forest Classifier** with an 83% accuracy score.
   - Evaluated using confusion matrix, classification report, and feature importance.

5. **📈 Business Insights:**
   - Customers with short tenure and month-to-month contracts were at higher risk.
   - Electronic check payment and higher monthly charges correlated with churn.

---

## ✅ Key Results

| Metric              | Result         |
|---------------------|----------------|
| Model               | Random Forest Classifier |
| Accuracy            | 83%            |
| Key Predictors      | Tenure, Contract Type, Monthly Charges |
| Churn Reduction Potential | ~20% via targeted retention strategies |

---

## 📸 Output Snapshots

### Churn Distribution  
![Churn Distribution](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Churn%20Distribution.png)

### Churn by Contract Type  
![Churn by Contract Type](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Churn%20by%20Contract%20Type.png)

### Churn by Gender  
![Churn by Gender](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Churn%20by%20Gender.png)

### Confusion Matrix  
![Confusion Matrix](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Confusion%20Matrix.png)

### Correlation of Features with Churn  
![Correlation of Features with Churn](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Correlation%20of%20Features%20with%20Churn.png)

### Distribution of Tenure  
![Distribution of Tenure](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Distribution%20of%20Tenure.png)

### Monthly Charges vs Churn  
![Monthly Charges vs Churn](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Monthly%20Charges%20vs%20Churn.png)

### Top 10 Important Features for Churn  
![Top 10 Important Features for Churn](https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-/raw/main/Images/Top%2010%20Important%20Features%20for%20Churn.png)

> 📂 All output visuals are available in the `images/` folder.

---

## 🚀 How to Run the Project

### 1. Clone the Repository
```bash
git clone https://github.com/ChandraShekharR07/Customer-Churn-Prediction-Python-SQL-.git
cd Customer-Churn-Prediction-Python-SQL-
