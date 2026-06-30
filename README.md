 # 📊 Sync or Sink — Labor Market Analysis
📌 Project Overview

Sync or Sink — Labor Market Analysis is an end-to-end data analytics project that explores the global labor market using salary and employment data. The project combines data preprocessing, cleaning, analysis, data modeling, and interactive visualization to uncover insights about salaries, education, experience, industries, and work modalities.
Using modern data analytics tools, the project transforms raw data into meaningful business intelligence that helps individuals, recruiters, and organizations better understand labor market trends and make informed decisions.

 # The project follows a complete analytics workflow:
Data Collection
Data Cleaning & Preprocessing
Data Modeling
Data Analysis
Interactive Dashboard Development
Business Insights & Reporting

 # 🎯 Project Objectives
Analyze salary distribution across different industries.
Study the impact of education on compensation.
Measure the effect of experience and seniority on salary.
Compare Remote, Hybrid, and On-site work models.
Discover salary gaps between different job categories.
Build interactive dashboards that support business decision-making.
 # 🗂️ Dataset
The project is based on a dataset containing over 250,000 salary records from different industries and countries.
The dataset includes information such as:

Job Title
Industry
Department
Years of Experience
Education Level
Certifications
Salary
Bonus
Tax Rate
Work Modality
Growth Percentage
🔄 Project Workflow
Raw Dataset
      │
      ▼
Data Cleaning (Python & Excel)
      │
      ▼
Data Preprocessing
      │
      ▼
Data Modeling (Star Schema)
      │
      ▼
Power BI
      │
      ▼
Interactive Dashboard
      │
      ▼
Business Insights
 # ⭐ Data Model — Star Schema
The project uses a Star Schema to improve query performance and simplify data analysis.
Fact Table
Fact_SalaryPerformance
Contains numerical business metrics including:
Annual Salary
Net Compensation
Tax Rate
Bonus
Salary Growth
Dimension Tables
Dim_Job
Job Title
Industry
Department
Work Modality
Required Skills
Dim_Experience
Years of Experience
Seniority Level
Previous Roles
Dim_Education
Degree Level
Certifications
Field of Study
 
 # 🛠️ Tools & Technologies
Tool	Purpose
Python (Pandas, NumPy)	Data cleaning & preprocessing
Microsoft Excel	Data validation, formatting & initial cleaning
Power BI Desktop	Data visualization & dashboard development
Power Query	Data transformation inside Power BI
DAX	Measures, KPIs & calculated columns
 # Star Schema	Data warehouse modeling
📈 Dashboard Features
📊 Salary Analysis
Average Salary
Median Salary
Salary Distribution
Salary Growth
 # 💼 Job Insights
Highest Paying Jobs
Salary by Industry
Salary by Department
Top Skills
# 🎓 Education Analysis
Salary by Degree
Salary by Certification
Field of Study Comparison
# 👨‍💼 Experience Analysis
Salary by Experience
Seniority Analysis
Career Growth
# 🌍 Work Analysis
Remote vs Hybrid vs On-site
Work Modality Distribution
# 📌 Interactive Features
Dynamic Filters
Drill-through Pages
Cross-filtering
KPI Cards
Trend Analysis
# 📊 Key Insights
The dashboard helps answer questions such as:

Which industries pay the highest salaries?
Does education significantly affect income?
How much does experience increase salary?
Which work modality offers the best compensation?
What skills are most associated with high-paying jobs?
 # 🚀 Getting Started
Prerequisites
Microsoft Power BI Desktop
Python 3.x (optional, for preprocessing)
Installation
git clone https://github.com/mahmoudtarek10/Sync_or_Sink.git

Open:

Sync_or_Sink.pbix

Explore:

Model View
Report View
Dashboard Pages
📂 Repository Structure
Sync_or_Sink/
│
├── Dashboard/
│   └── Sync_or_Sink.pbix
│
├── Dataset/
│   ├── Raw Data
│   └── Clean Data
│
├── Python/
│   └── Data_Preprocessing.ipynb
│
├── Images/
│
├── README.md
│
└── LICENSE
# 👥 Team
Mahmoud Tarek Hassan — Team Leader
Fares Hesham Mahmoud
Shahd Hassan Ahmed
Salma Mohamed Elhwary
Shahd Mohamed Elnahas
 # 🎓 Instructor

Eng. Kareem Bakly

📄 License

This project is developed for educational purposes.
