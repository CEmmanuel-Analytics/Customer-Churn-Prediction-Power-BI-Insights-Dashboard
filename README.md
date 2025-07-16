# 📉Customer-Churn-Prediction-Power-BI-Insights-Dashboard
This project analyzes and predicts customer churn using a real-world Telco dataset. It combines Python-based machine learning with a dynamic Power BI dashboard to provide actionable insights for business decision-making.

## 🔧 Tools Used
- **Python (Jupyter Notebook)**
  - Pandas, Scikit-learn, Matplotlib, Seaborn
- **Power BI**
- **DAX for calculated columns & measures**

## 🎯 Project Goals
- Predict customers likely to churn using Logistic Regression.
- Identify patterns and high-risk segments (by tenure, income, contract type, etc.).
- Build a clean, interactive dashboard to visualize key churn drivers and KPIs.
- Communicate data-driven strategies to reduce churn and retain customers.

## 🧪 Machine Learning Overview

### 📁 Dataset
- Source: Kaggle (Telco Customer Churn)
- 7,000+ rows, 20+ columns including:
  - Customer demographics
  - Services subscribed
  - Charges and tenure
  - Churn status (target variable)
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

### 🧼 Steps Performed in Python
- Data Cleaning & Null Handling
**Data Cleaning**
   - Converted `TotalCharges` to numeric and handled missing values.
   - Converted `Churn` from "Yes/No" to binary (1/0).
   - Removed `customerID` column.
- Feature Engineering:
  - `TenureGroup`, `IncomeGroup`, `ServiceCount`
- Label Encoding for Categorical Variables
- Logistic Regression Model
 **Model Building**
   - Split data (80% train / 20% test)
   - Trained a **Logistic Regression** model
   - Evaluated using metrics: accuracy, precision, recall, F1, ROC AUC
- Evaluation Metrics:
  - **Accuracy:** 80%
  - **ROC AUC Score:** 0.83
  - **Precision/Recall/F1 Report**

### 📊 Confusion Matrix

| Actual / Pred | Pred No | Pred Yes |
|---------------|---------|----------|
| **Actual No** | 920     | 113      |
| **Actual Yes**| 174     | 200      |

<img width="631" height="345" alt="Result " src="https://github.com/user-attachments/assets/8cf2e170-2e16-471f-86b8-b0874ee1d996" />

## 📊 Power BI Dashboard Highlights

### ✅ KPI Cards
- **Total Customers**: 7,000  
- **Total Churned**: 2,000  
- **Churn Rate**: 27%  
- **Total Revenue**: $16M  

### 📈 Visuals
- Churn by Tenure Group
- Churn by Gender and Income Group
- Revenue Breakdown by Churn (Pie Chart)
- Average Monthly Charges by Churn Status

### 📌 Slicers
- Gender
- Dependents
<img width="1168" height="656" alt="Churn Dashboard" src="https://github.com/user-attachments/assets/42516b33-9547-4493-a9a8-064d33e10963" />

## 🔍 Key Insights

- **27% of customers churned**, accounting for **$3M in lost revenue**.
- **Early-tenure customers (0–24 months)** show the highest churn.
- **High-income and high-monthly-charge customers** are churning more than expected.
- **Churned customers pay an average of $74/month**, vs. $61/month for retained.
- The ML model aligns well with dashboard findings and predicts churn with good accuracy.

## 📁 Repository Structure
├── customer_churn_prediction.ipynb # Python notebook with EDA + ML
├── cleaned_telco_churn.csv # Cleaned dataset
├── README.md # Project overview


## 🔗 Live Demo or Preview (Optional)

> Coming soon on LinkedIn or YouTube (stay tuned)

## 💼 Author

**Chibueze Emmanuel Chukwuma**  
Data Analyst | Excel| Python | SQL | Power BI  
 Nigeria | 🌍 Open to work onsite, Hybrid and Remote Roles

## Contact

- LinkedIn: [www.linkedin.com/in/emmanuel-chibueze-23b149344)
- GitHub: (https://github.com/CEmmanuel-Analytics/Customer-Churn-Prediction-Power-BI-Insights-Dashboar)
- Email: [echibueze770@gmail.com ]


## ⭐ If you found this useful, feel free to star the repo!


