# Deloitte-virtual-internship-data-analysis-task

📊 Forage Virtual Internship – Data Analyst @ Deloitte (Daikibo Case Study)

This repository contains the completed work from the Data Analytics Virtual Internship offered by Deloitte via Forage. This virtual internship simulated real-world data analytics tasks like analyzing machine downtime and pay equity across multiple global factories using Excel, Tableau, and basic data logic.

🏢 Internship Summary

Company: Deloitte
Client (Case): Daikibo
Platform: The Forage
Duration: Self-paced
Internship: Data Analyst Virtual Internship
Completed: July 2025
🧰 Tools & Skills Used

Tool	Purpose
Excel	Conditional formulas, classification logic
Tableau	Dashboard creation, bar charts, filters
JSON	Data import & unification
Data Viz	Storytelling through charts & dashboards
📁 Repository Contents

forage-data-analyst-deloitte/ ├── 📊 DownTime_Dashboard.png → Tableau dashboard screenshot ├── 📈 Equality_Table_Updated.xlsx → Excel sheet with classification ├── 🏅 Forage_Certificate.pdf → Internship completion certificate └── 📘 README.md → This file

✅ Tasks Completed

📌 Task 1: Machine Downtime Analysis (Tableau)

Goal: Help Daikibo identify the factory and machine types with the most downtime.

Steps:

Loaded telemetry data from a JSON file into Tableau.
Created a calculated field Unhealthy = 10 to represent 10 minutes of downtime for each "unhealthy" machine status.
Built two bar charts:
Down Time per Factory
Down Time per Device Type
Created a dashboard where selecting a factory filters the machines below.
📌 Task 2: Pay Equality Audit (Excel)

Goal: Classify job roles based on their compensation equality scores.

Given Columns:

Factory
Job Role
Equality Score (from -100 to +100)
Task: Add a fourth column called Equality Class with this logic:

=IF(ABS(C2)<=10,"Fair",IF(ABS(C2)<=20,"Unfair","Highly Discriminative"))
