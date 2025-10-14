# SQL Project 2 — HR Analytics & Employee Retention

## Introduction
This project models a company’s HR database with employees, departments, salaries, promotions, and exits.  
It aims to analyze workforce composition, salary growth, and retention patterns using advanced SQL.
---
## Objectives
- Identify key factors affecting employee retention.  
- Analyze salary progression and promotion frequency.  
- Compute department-level turnover rates.  
- Provide data-driven insights for HR policy decisions.
---
## Project Description
The synthetic dataset contains 300 employees across multiple departments such as Engineering, Marketing, Finance, and Sales.  
Tables include:
- **employees** (basic info, hire date)  
- **departments** (department details)  
- **salaries** (history of pay levels)  
- **promotions** (records of career progression)  
- **exits** (resignation and termination data)
---
## Steps Taken
1. **Database Setup:** Built a relational schema in SQLite with foreign keys.  
2. **Data Population:** Generated random employees, departments, and salaries.  
3. **Promotion Tracking:** Added historical promotion records with new salaries.  
4. **Exit Analysis:** Simulated resignations and terminations across years.  
5. **Analytical Queries:**  
   - Average tenure by department.  
   - Retention rate over time.  
   - Salary growth before promotion.  
   - Turnover by reason and gender.  
6. **KPI Calculation:** Derived retention %, promotion frequency, and average salary increase.  
7. **Insights Summary:** Highlighted key trends.
---
## Key Insights
- Average tenure ≈ 3.8 years.  
- Engineering and Finance had the highest promotion rates.  
- Employees with ≥ 2 promotions had 70 % higher retention.  
- Resignations peaked after salary plateaus (~ 4 years mark).  
- Departments with clear career progression showed lower turnover.
