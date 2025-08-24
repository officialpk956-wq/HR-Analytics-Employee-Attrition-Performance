
# Employee Attrition Analysis & Predictive Modeling

Welcome to the Employee Attrition Analysis project. This repository provides a complete exploration of factors driving employee turnover, predictive modeling for attrition, and actionable insights for HR decision-making.

---

## 📌 Project Overview

Employee attrition has a direct impact on organizational performance and costs. This project aims to:
- Identify **key drivers of attrition**
- Analyze patterns by **department, job role, age, tenure, and other demographics**
- Build **predictive models** to identify high-risk employees
- Provide actionable **recommendations for retention strategies**

---

## 🗂️ Dataset

The dataset used is the IBM HR Analytics Employee Attrition dataset, which includes features such as:
- **Demographics**: Age, Gender, Marital Status, Education, etc.
- **Job Information**: Department, Job Role, Job Level, TotalWorkingYears
- **Performance & Satisfaction**: EnvironmentSatisfaction, JobSatisfaction, TrainingTimesLastYear
- **Compensation & Benefits**: MonthlyIncome, StockOptionLevel, Overtime
- **Attrition**: Yes/No label indicating if the employee left

**Rows × Columns**: 1470 × 35  
**Overall Attrition Rate**: ~16.1%

---

## 📊 Exploratory Data Analysis

**Key Visualizations:**
- Attrition by **Department**, **Job Role**, **Age Band**, **Tenure**, and **Income Band**
- Attrition vs **OverTime**, **BusinessTravel**, **MaritalStatus**, **JobSatisfaction**
- Heatmaps of **JobRole × Department** attrition





---

## 🔍 Predictive Modeling

### Logistic Regression
- Achieved **ROC-AUC = 1.0**
- **Top Risk Factors**: OverTime, early tenure, lower Job/Environment Satisfaction, Age, MonthlyIncome

### Random Forest
- Captures **non-linear relationships**
- **Top 10 Features** driving attrition visualized:



- Risk scores assigned to all employees
- Employees segmented into **High / Medium / Low Risk** bands for proactive HR intervention

**Example: Top 10 High-Risk Employees**
| EmployeeNumber | Attrition | Risk Score | Risk Band |
|----------------|-----------|------------|-----------|
| 622            | Yes       | 0.968      | High Risk |
| 167            | Yes       | 0.953      | High Risk |
| 1624           | Yes       | 0.953      | High Risk |
| 1433           | Yes       | 0.950      | High Risk |
| 1928           | Yes       | 0.948      | High Risk |

---

## 📝 Key Insights

- Employees with **high overtime**, **short tenure**, **lower income**, and specific **job roles** are most likely to leave.
- Early-career employees (≤1 year tenure) and younger cohorts (18–34) are high-risk groups.
- Attrition can be mitigated through **compensation adjustments**, **managerial coaching**, **mentoring**, and **risk-based monitoring**.

---

## 🚀 Recommendations

1. **Retention Levers**
   - Adjust compensation for at-risk employees
   - Expand stock/equity options for critical roles

2. **Managerial Levers**
   - Provide coaching and mentorship
   - Enhance recognition and career development

3. **Structural Levers**
   - Improve onboarding programs
   - Implement hybrid/remote options for high-travel roles

4. **Monitoring**
   - Use **risk bands** and dashboards to track attrition
   - Evaluate interventions monthly for effectiveness

---



