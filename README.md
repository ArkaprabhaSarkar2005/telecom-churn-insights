# 📊 Customer Churn Analysis

This repository contains a detailed analysis of customer churn using telecom data. The goal is to understand why customers leave a telecom service and identify the key features influencing their decision to churn. The analysis includes data cleaning, transformation, exploratory visualizations, and interpretation of important patterns to support business decision-making and customer retention strategies.

---

## 📁 Dataset

The dataset used is **Customer Churn.csv**, which includes the following fields:

- **Demographic Information**: Gender, SeniorCitizen, Partner, Dependents  
- **Account Information**: Tenure, Contract, PaymentMethod, MonthlyCharges, TotalCharges  
- **Service Information**: PhoneService, InternetService, OnlineSecurity, TechSupport, StreamingTV, etc.  
- **Target**: `Churn` (Yes/No)

---

## 🧰 Technologies Used

- **Python 3.x**  
- **Pandas** – data manipulation  
- **NumPy** – numerical computation  
- **Matplotlib / Seaborn** – data visualization  
- **Jupyter Notebook** – for interactive analysis

---

## 📊 Analysis Overview

### 1. **Data Cleaning**
- Replaced blank entries in `TotalCharges` with zero and converted it to float.
- Checked for missing values and ensured proper data types.
- Converted `SeniorCitizen` from 0/1 to "no"/"yes" for clarity.

### 2. **Exploratory Data Analysis (EDA)**
- **Churn Distribution**: ~26.54% of customers have churned.
- **Demographic Factors**:
  - Senior citizens churn more (in % terms) than others.
  - Gender does not significantly affect churn rate.
- **Behavioral Patterns**:
  - Customers with short tenure (1–2 months) are most likely to churn.
  - Customers with month-to-month contracts churn the most.
- **Service Factors**: Analysis also includes service type impact (to be expanded if applicable).

### 3. **Visualizations**
- Countplots, histograms, pie charts, and stacked bar plots were used to visualize:
  - Churn by senior citizen status
  - Churn by gender
  - Churn across contract types
  - Churn distribution over tenure

---

## 🔍 Key Insights

| Factor             | Observation |
|-------------------|-------------|
| **Churn Rate**     | ~26.5% of customers have churned |
| **Senior Citizens**| Higher churn percentage |
| **Tenure**         | Short-tenure customers churn more |
| **Contract Type**  | Month-to-month plans show highest churn |
| **Gender**         | No major impact on churn |

---

## 📂 Project Structure

```
📦 churn-analysis/
 ┣ 📄 Customer Churn.csv
 ┣ 📓 Churned_Analysis.ipynb
 ┣ 📄 README.md
```

---

## 📌 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/customer-churn-analysis.git
   cd customer-churn-analysis
   ```

2. Open the notebook:
   ```bash
   jupyter notebook Churned_Analysis.ipynb
   ```

3. Run cells to view the entire exploratory analysis.

---

## 🏁 Next Steps (Optional)

- Add predictive modeling (e.g., logistic regression, random forest)  
- Perform feature importance analysis  
- Deploy churn prediction model using Streamlit or Flask  

---

## 📜 License

This project is free to use for **educational, academic, and commercial purposes**.  
You may **reuse, modify, share, and distribute** this work with appropriate credit. No restrictions apply.

---

## 🙌 Acknowledgments

- Dataset Source: [Kaggle / IBM Sample Dataset]  
- Inspired by real-world business challenges in customer retention and analytics.

---

## 📬 Contact

**Arkaprabha Sarkar**  
📧 Email: s.arkaprabha@iitg.ac.in  
🔗 LinkedIn: [https://www.linkedin.com/in/arkaprabha-sarkar-5b6302287](https://www.linkedin.com/in/arkaprabha-sarkar-5b6302287)
