# 📊 Employee Attrition Analysis
**End-to-End Data Analytics Project**

---

## 📌 Project Overview

Employee attrition is a critical challenge for organizations as it impacts productivity, cost, and workforce stability.  
This project analyzes employee attrition data to identify trends and factors influencing employees leaving the organization.

The project demonstrates a complete **data analytics workflow** using **Python, MySQL Workbench, and Power BI**.

---

## 🎯 Project Objectives

- Clean and prepare raw HR data for analysis  
- Perform exploratory data analysis and visualization  
- Conduct SQL-based analysis for business insights  
- Build an interactive Power BI dashboard  

---

## 📂 Dataset Information

- **Source:** Kaggle  
- **Dataset Name:** IBM HR Analytics Employee Attrition Dataset  
- **Link:** https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset  
- **File Used:** `WA_Fn-UseC_-HR-Employee-Attrition.csv`

Each row represents one employee with demographic, job-related, and compensation details.

---

## 🛠 Tools & Technologies

- **Python** (Pandas, Matplotlib, Seaborn)
- **MySQL Workbench**
- **Power BI Desktop**
- **Google Colab / Jupyter Notebook**

---

## 🧹 Data Cleaning & Preparation (Python)

Steps performed in Python:

- Removed unnecessary and constant columns  
- Converted `Attrition` from Yes/No to numeric (1/0)  
- Standardized column names  
- Performed exploratory data analysis  
- Exported cleaned data as CSV  

**Output file:**  
`hr_attrition_cleaned.csv`

---

## 📈 Exploratory Data Analysis

Visualizations created include:

- Attrition distribution (Stayed vs Left)
- Attrition by department
- Monthly income comparison by attrition

These visuals helped identify early trends in employee behavior.

---

## 🧮 SQL Analysis (MySQL Workbench)

- Created database and tables  
- Imported cleaned CSV using **Table Data Import Wizard**  
- Executed SQL queries to analyze:
  - Attrition rate
  - Attrition by department
  - Average income by attrition status

---

## 📊 Power BI Dashboard

The Power BI dashboard includes:

- **KPI Cards**
  - Total Employees
  - Attrition Rate
- **Visuals**
  - Attrition by Department
  - Attrition by Job Role
  - Income comparison by attrition
- **Interactive Filters**
  - Gender
  - Department
  - Job Role

Custom **DAX measures** were created to calculate business KPIs.

---

## 🔍 Key Insights

- Certain departments experience higher attrition  
- Employees with lower monthly income are more likely to leave  
- Job role and department significantly influence attrition  

---

## ✅ Conclusion

This project shows how data analytics can be applied to solve real-world HR problems.  
By combining Python, SQL, and Power BI, the analysis provides actionable insights for decision-making.

---

## 🚀 Future Enhancements

- Predict attrition using machine learning models  
- Include employee engagement and performance data  
- Add time-based attrition trend analysis  

---

## 👤 Author

**Your Name**  
Data Analyst Bootcamp (8 Weeks)

---

## ⭐ Acknowledgements

- Kaggle for providing the dataset  
- Bootcamp instructors for guidance and support  
