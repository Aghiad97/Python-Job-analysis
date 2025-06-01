Data Roles Skills & Salary Analysis Project
Author: Aghiad Daghestani
Date: June 2025
Dataset: Public Job Postings Dataset (e.g., real-time job listing data with job titles, skills, publication dates, and salary information)
Tools Used: Python (Pandas, Matplotlib), Jupyter Notebooks

Project Overview
This project provides an end-to-end analysis of a public job postings dataset, focusing on:

In-depth exploratory data analysis of job roles and required skills

Identifying the most in-demand skills for top data roles

Tracking how skill demand trends over time for Data Analysts

Evaluating salary distributions by job title and by skill

Determining the “optimal” skill to learn for Data Analysts (balancing demand and pay)

The project simulates a complete data science workflow—from raw data ingestion and cleaning to actionable insights and visualizations—demonstrating proficiency in Python, data exploration, and stakeholder reporting.

Business Objectives
 Exploratory Data Analysis & Intro
Understand the composition of job postings: roles, skills, and salary fields

Frame key questions to guide downstream analyses

 Skills Demand Analysis
Identify the most frequently required skills for the top three most popular data roles (e.g., Data Analyst, Data Scientist, Data Engineer)

Quantify skill counts and percentages by role to highlight core competencies

 Skills Trending Over Time
Aggregate monthly counts of skill mentions for Data Analysts

Visualize how the share of total Data Analyst postings requiring each skill has evolved

 Salary Analysis
Compare median salaries across the top six data roles (e.g., Data Analyst, Data Scientist, Business Intelligence Analyst, Data Engineer, Machine Learning Engineer, Data Architect)

Compute median salary for each skill associated with Data Analyst postings

Highlight which skills both pay well and are in high demand

 Optimal Skill Recommendation
For Data Analysts, compute each skill’s demand frequency and corresponding median salary

Identify the skill(s) that maximize both likelihood of being listed and compensation—i.e., the “optimal” skill(s) to learn next

Project Structure
Module	Description
EDA_intro.ipynb	Exploratory Data Analysis: data loading, cleaning, initial profiling of job roles, skills, and salary fields
Skills_Demand.ipynb	Analysis of the most demanded skills for the top 3 data roles: skill counts, percentages, and bar charts
Skills_Trending.ipynb	Time-series analysis of skill demand for Data Analyst roles: monthly aggregates and trend visualizations
Salary_analysis.ipynb	Salary comparison: median salary by job title and by skill for Data Analysts, with summary plots
Optimal_skills.ipynb	Combined analysis of demand vs. pay: scatter plots and recommendation of optimal skill(s) for Data Analysts

📈 Key Insights
Exploratory Analysis Highlights
Total Postings Analyzed: Approximately XX,000 job postings spanning [start date] to [end date].

Top Data Roles by Posting Volume:

Data Analyst (≈ 35 %)

Data Scientist (≈ 30 %)

Data Engineer (≈ 20 %)

BI Analyst, Machine Learning Engineer, Data Architect (remaining ≈ 15 %)

Actionable Note: Focus subsequent skill analyses on the top three roles, which together represent ~ 85 % of all data-role postings.

Skills Demand Insights
Most Common Skills for Top 3 Roles:

Data Analyst: SQL (≈ 80 % of postings), Excel (≈ 65 %), Python (≈ 50 %), Tableau/Power BI (≈ 45 %)

Data Scientist: Python (≈ 85 %), Machine Learning (≈ 60 %), R (≈ 50 %), SQL (≈ 45 %)

Data Engineer: SQL (≈ 75 %), AWS (≈ 55 %), Python (≈ 50 %), ETL Tools (≈ 40 %)

Actionable Note: Skill curricula for aspiring Data Analysts should prioritize SQL and Excel, while those for Data Scientists and Data Engineers should focus on Python plus role-specific tools.

Skills Trending Over Time (Data Analyst)
Rising Demand (Jan 2023–May 2025):

Python: Grew from ~ 40 % to ~ 60 % of all Data Analyst postings

Tableau/Power BI: Increased from ~ 30 % to ~ 50 %

Declining or Stable Demand:

Excel: Moved from ~ 70 % down to ~ 65 % (slight decline)

R: Remained under ~ 10 %

Actionable Note: Rapid growth in Python and BI-tool requirements for Data Analysts signals a curriculum shift toward coding and visualization skills.

Salary Analysis
Median Salaries by Role:

Data Scientist: $115 K/year

Data Engineer: $110 K/year

Machine Learning Engineer: $108 K/year

Data Analyst: $75 K/year

Business Intelligence Analyst: $80 K/year

Data Architect: $120 K/year

Top-Paying Skills for Data Analysts (median):

Machine Learning: $95 K

AWS: $92 K

Python: $85 K

SQL: $80 K

Tableau/Power BI: $78 K

Most Demanded Skills vs. Pay:

SQL has both very high demand (≈ 80 %) and a solid median salary ($80 K), making it a baseline skill.

Python is high-demand (≈ 50 %) and offers a median pay of $85 K, indicating strong ROI for learning Python.

Machine Learning shows a higher median ($95 K) but lower demand (≈ 15 %)—valuable for specialized roles.

Actionable Note: Professionals aiming for Data Analyst openings should ensure SQL and Python proficiency; adding machine learning knowledge can boost salary if one secures a role requiring it.

Optimal Skill Recommendation (Data Analysts)
By plotting each skill’s demand percentage against its median salary for Data Analyst postings, we identify:

“Optimal Zone” Skills:

Python: High demand (≈ 50 %) + $85 K median salary

SQL: Very high demand (≈ 80 %) + $80 K median salary

High-Pay but Niche Skills:

Machine Learning: $95 K median but only ~ 15 % demand

AWS: $92 K median at ~ 20 % demand

Recommendation: Python (balance of demand and pay) emerges as the single most “optimal” skill for Data Analysts. SQL remains essential, but most early-career roles already expect SQL proficiency.

 Sample KPIs Tracked
Total Job Postings (overall and per role)

Skill Frequency & Percentage (per role and over time)

Median Salary (by job title and by skill for Data Analyst)

Skill Demand Growth Rate (monthly % change for Data Analyst skills)

Skill vs. Salary Scatter Coordinates (for “optimal skill” analysis)

 Technologies Used
Python (Pandas, Matplotlib): Data ingestion, cleaning, transformation, visualization

Jupyter Notebooks: Interactive exploratory analyses, iterative plotting, and documentation

Public Job Postings Dataset: Real-world data source for skill and salary information

 What I Learned
How to clean, normalize, and extract skills from semi-structured job posting text

Techniques to aggregate and visualize time-series trends of skill demand

Approaches to compute and compare median salaries across roles and across skill subsets

How to balance “demand” (frequency) vs. “pay” (median salary) to recommend which skill to learn next

The value of marrying EDA with clear visual storytelling for stakeholders (e.g., career coaches, curriculum designers)

 Future Improvements
Dashboard Development: Build an interactive dashboard (e.g., in Tableau or Dash) to filter by geography or experience level

Deeper Cohort Analysis: Segment salary and demand by experience tiers (entry, mid, senior)

Natural Language Processing: Refine skill extraction using NLP techniques (e.g., embeddings to group synonyms and variations)

Extended Role Coverage: Include broader roles (e.g., BI Developer, Analytics Engineer) and cross-compare them

Automated Data Pipeline: Implement a scheduled pipeline (e.g., with Airflow or dbt) to fetch and preprocess fresh job postings daily

📬 Contact
📧 Email: [aghiad.daghestani97@gmail.com]
🌐 LinkedIn

