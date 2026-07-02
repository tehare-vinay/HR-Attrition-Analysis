# HR Attrition Analysis

## Overview
Analysis of IBM HR Analytics dataset (1,470 employee records, 35 columns) 
to identify key factors driving employee attrition, using Python, SQL, 
and Power BI.

## Key Findings
- Sales Representatives have the highest attrition rate (~40%)
- Employees working OverTime show nearly 3x higher attrition
- Employees under 30 are the most at-risk age group

## Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn) — data cleaning & EDA
- **SQL (SQLite)** — querying attrition patterns by department/role
- **Power BI** — interactive dashboard with DAX measures

## Files
- `hr_attrition_analysis.ipynb` — full analysis notebook
- `HR_Attrition_Cleaned.csv` — cleaned dataset
- `HR_Attrition.db` — SQLite database for SQL queries

## Visualizations

### Attrition by Department
![Attrition by Department](attrition_by_deparment.png)

### Attrition by OverTime
![Attrition by OverTime](attrition_by_overtime.png)

### Age vs Attrition
![Age vs Attrition](age_vs_attrition.png)

### Attrition by Job Role
![Attrition by Job Role](attrition_by_jobrole.png)

### Monthly Income vs Attrition
![Monthly Income vs Attrition](monthlyincome_vs_attrition.png)

### Correlation Heatmap
![Correlation Heatmap](correlation_heatmap.png)

## Status
🔄 In Progress — Power BI dashboard under development

## Author
Vinay Tehare | [LinkedIn](https://www.linkedin.com/in/vinay-tehare)
