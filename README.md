# 🏦 Loan Default Risk Analysis (CRISP-DM Case Study)

## 📘 Overview
A data-driven analysis of personal loan default risk, following the CRISP-DM methodology.  
Tools used: SQL, Excel, Power BI, and Python.

---

## 🔍 1. Business Understanding
A retail bank wanted to understand the characteristics of clients likely to default on loans, 
to improve credit scoring and reduce risk exposure.

**Main Questions**
- What borrower behaviors correlate most with default?
- Can we predict the probability of default with basic variables?

---

## 🧠 2. Data Understanding
Source: Public dataset (Credit Risk Kaggle).  
10 variables, 150,000+ observations.

| Variable | Description |
|-----------|--------------|
| SeriousDlqin2yrs | Binary target variable |
| RevolvingUtilizationOfUnsecuredLines | % utilization of credit lines |
| ... | ... |

Initial findings:
- 6.7% of customers defaulted.
- Missing values in MonthlyIncome and NumberOfDependents.

---

## 🧹 3. Data Preparation
Data cleaning done in **SQL + Excel**:
- Removed duplicates and nulls.
- Calculated Debt-to-Income Ratio.
- Standardized column names.

---

## 📈 4. Exploratory Data Analysis (Excel/Power BI)
- High DebtRatio and missed payments → strong link to default.
- Younger borrowers (<25) had higher default rates.
- Visuals: bar charts, heatmaps, and correlation matrix.

---

## 🤖 5. Modeling (Python, optional)
Trained a simple Logistic Regression model:
- Accuracy: ~74%
- Precision: 0.68
- Key coefficients: DebtRatio, 90-day late, Revolving Utilization

---

## 💡 6. Evaluation & Insights
- Most influential factors in default risk were delinquency frequency and high credit utilization.
- Model interpretability makes it useful for business decision support.

---

## 📊 7. Deployment / Reporting
Delivered dashboard in **Power BI** with key metrics:
- Default Rate by Age Group
- Credit Utilization vs. Default
- Top 3 Predictive Indicators

---

## 🧩 Tools Used
SQL | Excel | Power BI | Python (Pandas, scikit-learn)

---

## 🧠 Key Learnings
- Real-world credit data cleaning challenges
- Translating analytics into risk insights
- Combining SQL + Excel + Python effectively

---

## 📁 Files
- `SQL_Cleaning_Script.sql`
- `EDA_Pivot_Tables.xlsx`
- `Loan_Risk_Dashboard.pbix`
- `README.md`

---

## 👨‍💻 Author
Pedro Daim [linkedin.com\in\data-daim]  
📫 [pdaim.analytics@gmail.com]

