# HR Employee Attrition Analysis Power BI Project

## 1. Introduction

This project aims to analyze employee attrition within an organization using Power BI. By examining various factors contributing to attrition, we aim to identify key trends, potential root causes, and provide actionable insights for HR to develop retention strategies. The analysis will cover aspects such as gender, job roles, satisfaction levels, salary, age group, educational background and years at company.

## 2. Data Source

The primary source of the data for this project is [https://drive.google.com/drive/folders/18mQalCEyZypeV8TJeP3SME_R6qsCS2Og].The original dataset contains 1480 rows and 38 columns including EmpID, Age, AgeGroup, Attrition, BusinessTravel, DailyRate, Department, DistanceFromHome, Education, EducationField, EmployeeCount, EmployeeNumber, EnvironmentSatisfaction, Gender, HourlyRate,
JobInvolvement, JobLevel, JobRole, JobSatisfaction, MaritalStatus, MonthlyIncome, SalarySlab, MonthlyRate, NumCompaniesWorked, Over18, OverTime, PercentSalaryHike, PerformanceRating, RelationshipSatisfaction,StandardHours, StockOptionLevel, TotalWorkingYears, TrainingTimesLastYear, WorkLifeBalance, YearsAtCompany, YearsInCurrentRole, YearsSinceLastPromotion, YearsWithCurrManage.

 ## 3. Data Cleaning and Transformation

* **Duplicated Records:** Removed Duplicates from EmpID to prevent skewed results.
* **Unneccessary Data:** Removed YearsWithCurrManager column as it's not relevant to our analysis.
 
## 4. Objectives 

* To visualize attrition on the basis of  different job roles, employee satisfaction, gender, salary etc.
* To provide data-driven insights and recommendations for improving employee retention.

## 5. Key Performance Indicators (KPIs)

* **Total Employee:** Total no of employees in the company.
* **Attrition Rate:** Percentage of employees who have left the company.
* **Attrition Count:** Total count of employees who have left.
* **Avg Years:** Average year after which employee tend to left the company.
* **Avg Salary:** Average annual income of the employee.
* **Average Age:** Average age of all the employees in the company.

## 6. Visualizations and Dashboard Highlights

The Power BI dashboard includes interactive visualizations to explore attrition from various angles:

* **TreeMap:** To visualize attribition rate by gender.
* **Donut Chart:** To denote the attribution rate in percentage on the basis of educational background.
* **Stacked Column Chart:** Sum of attrition count by age group.
* **Matrix:** To show the relation between Job satisfaction and attrition among different roles.
* **Stacked Bar Chart:** To show attribition on the basis of monthly salary and Job roles.
* **Stacked Area Chart:** Attrition by years spent at the company.

![Attrition on the basis of various paramenters](./images/Screenshot%20(269).png)
*This visualization defines attrition on the basis of various parameters*

## Insights and Recommendations

* **Gender-Based Attirition:** It can be seen that more males leave the company comparing to females. More gender specific policies should be implemented to address the concerns of specific genders.





