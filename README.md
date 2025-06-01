Data Roles Skills & Salary Analysis Project
Author: Aghiad Daghestani
Date: June 2025
Dataset: Public Job Postings Dataset
Tools Used: Python (Pandas, Matplotlib), Jupyter Notebooks

Project Overview
Analyzed a public job‐postings dataset to:

Profile job roles and required skills

Identify in‐demand skills for top data roles

Track skill trends over time for Data Analysts

Compare salaries by role and by skill

Recommend the “optimal” skill for Data Analysts (balancing demand and pay)

Business Objectives
🔹 EDA & Intro
Load and clean data

Profile job roles, skills, and salary fields

🔹 Skills Demand Analysis
Rank top skills for the three most common roles (Data Analyst, Data Scientist, Data Engineer)

Compute counts and percentages

🔹 Skills Trending Over Time
Aggregate monthly counts of key skills for Data Analysts

Visualize how each skill’s share changes

🔹 Salary Analysis
Compare median salaries across top six data roles

Compute median salary per skill for Data Analysts

🔹 Optimal Skill Recommendation
For Data Analysts, plot demand (%) vs. median salary for each skill

Identify skills with strong demand‐to‐pay balance

Project Structure
Module	Description
EDA_intro.ipynb	Load/clean data, initial profiling of roles, skills, and salaries
Skills_Demand.ipynb	Count and percentage of top skills for Data Analyst, Data Scientist, Data Engineer
Skills_Trending.ipynb	Monthly trend analysis of Data Analyst skills
Salary_analysis.ipynb	Median salary by role; median salary by skill for Data Analysts
Optimal_skills.ipynb	Combine demand vs. pay to recommend top skill(s) for Data Analysts

 Key Insights
Top Roles (by volume): Data Analyst (~35 %), Data Scientist (~30 %), Data Engineer (~20 %); others ~15 %.

Most Common Skills:

Data Analyst: SQL, Excel, Python, Tableau/Power BI

Data Scientist: Python, Machine Learning, R, SQL

Data Engineer: SQL, AWS, Python, ETL tools

Skill Trends for Data Analysts (Jan 2023–May 2025):

Python: ~40 → 60 %

Tableau/Power BI: ~30 → 50 %

Excel: ~70 → 65 %

R: <10 % steady

Median Salaries (annual):

Data Scientist $115 K, Data Engineer $110 K, ML Engineer $108 K, Data Architect $120 K

Data Analyst $75 K, BI Analyst $80 K

Top‐Paying Skills for Data Analysts: ML ($95 K), AWS ($92 K), Python ($85 K), SQL ($80 K), Tableau/Power BI ($78 K)

Optimal Skill for Data Analysts:

Python: ~50 % demand, $85 K median → best balance

SQL remains essential (high demand, solid pay)

 Sample KPIs Tracked
Total job postings (overall/by role)

Skill frequency & percentage (by role/over time)

Median salary (by role/by skill)

Monthly skill demand growth rates

Demand vs. salary coordinates for “optimal skill” analysis

 Technologies Used
Python (Pandas, Matplotlib): Data cleaning, aggregation, visualization

Jupyter Notebooks: Interactive analysis and plots

Public Job Postings Dataset: Real-world source for roles, skills, and salaries

 What I Learned
Cleaned and extracted skills from semi-structured text

Aggregated and visualized time-series skill trends

Compared median salaries across roles and skill subsets

Balanced “demand” vs. “pay” to recommend next skill

Presented insights clearly to guide career or curriculum decisions

 Future Improvements
Build an interactive dashboard (e.g., Tableau, Dash) for filtering by location/experience

Segment analysis by experience level (entry, mid, senior)

Enhance skill extraction with NLP (synonym grouping)

Expand to other roles (BI Developer, Analytics Engineer)

Automate data pipeline for daily updates (Airflow, dbt)

📬 Contact
📧 Email: [aghiad.daghestani97@gmail.com]
🌐 LinkedIn
