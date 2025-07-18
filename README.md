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

## 7. Insights and Recommendations

* **Gender-Based Attirition:** It can be seen that more males leave the company comparing to females. More gender specific policies should be implemented to address the concerns of specific genders.

* **Age-Based Attirition:** Age 26-35 have the highest rate of attirition. People in this age group are usually mid-level professionals hence they are more likely to leave for better opportunities. Creating a better employee retention policy such as giving them paid leaves, increase in their ESOPs component and providing better opportunity in organization itself.

* **Education-Based Attirition:** People in Technical, Human Resources and Marketing have higher attirition rate. Need to make sure, that the job role aligns with their skill expectations.

* **Salary-Based Attirition:** People in lower salary slab have higher attirition rate. Reasses their salary structure and benchmark it according to the industry standard. Have a employee loyalty program like increase in thier ESOP's component after spending a particular amount of time in the organization.

* **Low satisfaction based Attirition:** Employees who rated low on satisfaction score have higher attrition rate. Improve the workload, avoid micromanaging, have a clear expectations, conduct mental health workshops monthly to improver their overall wellbeing.

* **Job based attirition:** Job roles such as Laboratory Technician and Sales Executive have high exit rates. Reasses their work condition by taking feedback from them and improve upon it.

## 8. Future  Scope
* Including other parameter such as Distance from Home and Martial Status to get another picture of attirition rate.
* Conduct an exit interview to take feedbacks from the employees and improve our work culture upon it.



