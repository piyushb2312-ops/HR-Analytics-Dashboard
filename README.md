# HR-Analytics-Dashboard
📊 HR Analytics Dashboard | Power BI
🔍 Project Overview
The HR Analytics Dashboard is an interactive Business Intelligence solution built using Power BI to analyze employee attrition patterns, workforce demographics, salary distribution, and job role trends within an organization.

This dashboard helps HR teams and business decision-makers identify the major factors contributing to employee attrition and supports data-driven workforce planning strategies.

🎯 Business Problem

Employee attrition directly impacts:
- Productivity
- Recruitment cost
- Employee morale
- Business continuity

The objective of this project is to:
- Analyze attrition trends
- Identify high-risk employee groups
- Understand salary and job role impact
- Improve employee retention strategies


🛠️ Tools & Technologies Used
- Power BI
- Power Query
- DAX
- Data Modeling
- Microsoft Excel / CSV Dataset


📌 Dashboard Features
✅ Employee Attrition Analysis
✅ Department-wise Filtering
✅ Salary Slab Analysis
✅ Age Group Analysis
✅ Education-wise Attrition
✅ Job Role Insights
✅ Dynamic KPI Cards
✅ Interactive Visualizations


📊 Key KPIs
| KPI | Value | |------|------| | Total Employees | 1470 | | Total Attrition | 237 | | Attrition Rate | 16.1% | | Average Age | 37 | | Average Salary | 6.5K | | Average Years at Company | 7.0 |


📈 Key Insights

🔹 Attrition by Age Group
- Highest attrition is observed in the 26–35 age group.
- Younger employees are more likely to leave the organization.
  
🔹 Attrition by Salary
- Majority of attrition comes from employees earning below 5K salary slab.
- Lower salary range employees show higher turnover risk.

🔹 Attrition by Job Role
Top affected job roles:
- Laboratory Technician
- Sales Executive
- Research Scientist
- Sales Representative

🔹 Attrition by Education
Employees from:
- Life Sciences
- Medical
- Marketing
- 

🔹 Department Analysis
The dashboard allows dynamic filtering across:
- Human Resources
- Research & Development
- Sales

to compare workforce trends across departments.


🧹 Data Cleaning & Transformation

Data preprocessing was performed using Power Query, including:

- Handling missing values
- Data type corrections
- Removing inconsistencies
- Creating calculated fields
- Data formatting and transformation


🧠 DAX Measures Used
Some important DAX calculations used in the project:

Attrition Rate = 
DIVIDE([Attrition Count], [Total Employees]) * 100

Average Salary = 
AVERAGE(Employee[MonthlyIncome])

Total Employees = 
COUNT(Employee[EmployeeNumber])

Attrition Count = 
CALCULATE(COUNT(Employee[Attrition]), Employee[Attrition] = "Yes")


📌 Business Recommendations
✅ Improve Employee Retention
Focus on employees:
- aged 26–35
- low salary slabs
- high attrition job roles

✅ Salary Optimization
Review compensation structure for lower salary employees to reduce turnover.

✅ Employee Engagement Programs
Conduct:
- career growth programs
- skill development initiatives
- employee satisfaction surveys

✅ Department-Level HR Strategies
Create customized retention strategies for departments with high attrition.
