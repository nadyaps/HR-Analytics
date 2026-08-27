# HR-Analytics

## Project Overview

HR Analytics Attrition & Performance is an HR analytics project that analyzes employee data to understand factors associated with employee turnover. The objective of this project is to identify employee groups with higher attrition risk, analyze workforce patterns, and provide data-driven recommendations to improve employee retention strategies. This project demonstrates an end-to-end data analytics workflow, including data preparation, exploratory analysis, dashboard development, and business insight generation using Microsoft Excel.

## Business Problem

Employee turnover can create significant challenges for organizations, including recruitment costs, productivity loss, and knowledge gaps.
The HR department wants to understand:
- What is the overall employee attrition rate?
- Which departments and job roles have the highest attrition?
- Are certain employee characteristics associated with higher turnover risk?
- How do factors such as income, overtime, age, and tenure relate to employee attrition?
- Which employee groups should be prioritized for retention strategies?

## Dataset Description

The dataset used in this project is the IBM HR Analytics Employee Attrition & Performance dataset from Kaggle. Uncover the factors that lead to employee attrition and explore important questions such as ‘show me a breakdown of distance from home by job role and attrition’ or ‘compare average monthly income by education and attrition’. This is a fictional data set created by IBM data scientists. https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel | Data analysis and dashboard development |
| Power Query | Data cleaning and transformation |
| PivotTable | Data aggregation and analysis |
| Excel Formula | Feature engineering and calculations |
| PivotChart | Data visualization | 
| Slicer | Interactive Dashboard Filtering | 

## Data Preparation

Data preparation was performed using Microsoft Excel and Power Query.

The following steps were performed:

### Data Cleaning
- Checked dataset structure and data types
- Identified missing values
- Checked duplicate records
- Removed irrelevant columns with constant values
- Standardized data formats

### Feature Engineering
New analytical features were created:
- Attrition Flag
  - Yes = 1
  - No = 0

- Age Group
  - <25
  - 25-34
  - 35-44
  - 45-54
  - 55+

- Income Band
  - Low
  - Lower Middle
  - Upper Middle
  - High

- Tenure Group
  - <2 Years
  - 2-5 Years
  - 6-10 Years
  - 10+ Years

These features were created to support employee segmentation and attrition analysis.

## Dashboard Preview
The dashboard provides an overview of employee attrition patterns through interactive visualizations.
Key dashboard sections:
- Employee Overview KPI
- Attrition Rate Job Role
- Attrition by Income Band
- Employee Left Distribution by Department
- Employee Left Distribution by Overtime
- Attrition by Age Group
- Attrition by Years at Company
- Attrition by Overtime
- Attrition by Gender
<img width="809" height="987" alt="image" src="https://github.com/user-attachments/assets/a7b38a2f-41e1-4792-98ce-4a5cd2f5386b" />

## Key Insights

### 1. Employee attrition is highest during the early stages of a career.
The 25–35 age group exhibits the highest attrition rate (47.26%), indicating that employees in the early-to-mid stages of their careers are more likely to leave the company.

### 2. Employees with 2–5 years of tenure face the highest risk of attrition.
Employees with 2–5 years of tenure have the highest attrition rate. Potential reasons for this include unmet career expectations, more attractive external opportunities, and a lack of internal promotions.

### 3. Job roles with the highest risk of attrition
Laboratory Technicians, Sales Executives, and Research Scientists face a high risk. Likely causes include target pressure, workload, and performance expectations.

### 4. Income brackets have a significant impact on the attrition rate.
Employees in the low-income bracket have a much higher attrition rate—45.57%—compared to those in the highest income bracket, who have a rate of 16.03%. This indicates that income is a key factor.

## Recommendations
### 1. Companies can implement career development programs for employees aged 25–34, provide clearer promotion pathways, and enhance mentoring and employee engagement programs.
### 2. The company focuses on retention programs for the second through fifth years, conducts career path discussions, and carries out performance-based salary reviews.
### 3. The company conducts employee satisfaction surveys specifically for high-risk roles, as well as workload evaluations and reviews of compensation and career progression.
### 4. Companies can conduct salary benchmarking, evaluate entry-level compensation, and provide additional benefits for low-income employees.
