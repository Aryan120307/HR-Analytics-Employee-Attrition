# HR Analytics: Employee Attrition Analysis using Python

## 📌 Project Overview

Employee attrition is a major challenge for organizations, leading to increased hiring costs, productivity loss, and team disruption.

This project analyzes employee data to identify key factors that influence why employees leave a company and provides actionable, data-driven insights to support HR decision-making.

The project covers:

* Data Cleaning & Preparation
* Exploratory Data Analysis (EDA)
* Visualization of Attrition Trends
* Business Insight Generation

---

## 🎯 Problem Statement

High employee turnover negatively impacts organizational performance and financial stability.

The objective of this project is to:

* Understand the major factors contributing to employee attrition
* Identify high-risk employee groups
* Provide data-driven recommendations to reduce churn
* Support HR teams in improving retention strategies

**Target Variable:**

* `left` → 1 = Employee left the company
* `left` → 0 = Employee stayed with the company

---

## 📂 Dataset Description

The dataset contains HR records of employees, including performance metrics, workload, salary, and department information.

**Key Features:**

* satisfaction_level
* last_evaluation
* number_project
* average_montly_hours
* time_spend_company
* Work_accident
* left (Target Variable)
* promotion_last_5years
* dept
* salary

**Dataset Shape:**

* Rows: <add_rows_here>
* Columns: <add_columns_here>

Source: Kaggle / Internal HR Dataset

---

## 📌 Feature Description & Hypothesis

### 1. satisfaction_level

Represents how satisfied an employee is with the company.
Scale: 0 to 1 (higher = more satisfied)

Hypothesis:

* Lower satisfaction levels are likely to result in higher attrition
* Disengaged employees are more likely to leave

---

### 2. last_evaluation

The employee’s most recent performance score.

Hypothesis:

* Employees with very low scores may leave due to poor performance pressure
* Employees with very high scores may leave due to lack of recognition or better external offers

---

### 3. number_project

Number of projects currently handled by the employee.

Hypothesis:

* Employees with too few projects may feel undervalued
* Employees with too many projects may feel overworked and burned out
* Both extremes increase attrition risk

---

### 4. average_montly_hours

Average number of hours an employee works per month.

Hypothesis:

* Excessive working hours may lead to burnout
* Very low hours may indicate disengagement

---

### 5. time_spend_company

Total number of years the employee has spent in the company.

Hypothesis:

* Mid-tenure employees may leave if they see no growth opportunities
* Long-serving employees without promotion may also show higher churn

---

### 6. Work_accident

Indicates whether the employee experienced a workplace accident.
Values:

* 0 = No
* 1 = Yes

Hypothesis:

* Employees who had an accident may feel unsafe or dissatisfied

---

### 7. promotion_last_5years

Indicates whether the employee received a promotion in the last 5 years.
Values:

* 0 = No
* 1 = Yes

Hypothesis:

* Employees without promotions may feel stagnant and leave

---

### 8. dept

The department in which the employee works.

Hypothesis:

* Some departments may have higher attrition due to workload or culture

---

### 9. salary

The salary level assigned to the employee.
Categories:

* Low
* Medium
* High

Hypothesis:

* Low salary employees may leave due to financial dissatisfaction
* High salary employees may leave due to better external opportunities

---

## 🛠 Tools & Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## 🔍 Analysis Workflow

1. Data Loading & Inspection
2. Data Cleaning (missing values, data types, duplicates)
3. Exploratory Data Analysis (EDA)
4. Univariate & Bivariate Analysis
5. Visualization of attrition trends
6. Business Insight Generation
7. Final Recommendations

---

## 📊 Key Insights

(Add your actual results here after final analysis)

* Employees with low satisfaction levels show a significantly higher attrition rate
* Sales and Support departments experience the highest churn
* Employees in the low salary band are more likely to leave
* Employees handling too many projects show burnout-driven exits
* Both very low and very high working hours correlate with increased attrition
* Employees with long tenure without promotion are more likely to leave

---

## 💡 Business Recommendations

* Introduce employee engagement programs for low-satisfaction groups
* Optimize workload distribution to prevent burnout
* Implement retention bonuses and salary revisions for high performers
* Improve working conditions in high-attrition departments
* Establish structured career growth and promotion paths

---

## ✅ Conclusion

This HR Analytics project demonstrates how data-driven insights can help organizations reduce employee attrition.

By identifying churn drivers such as low satisfaction, workload imbalance, salary disparities, and departmental differences, HR teams can take proactive steps to improve employee retention.

Future Improvements:

* Build a machine learning model to predict attrition
* Create an interactive dashboard
* Automate churn monitoring pipelines

---

## 👤 Author

**Aryan**

