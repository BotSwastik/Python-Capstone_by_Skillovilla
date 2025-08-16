#Project: Capstone – Python Fundamentals
Situation: Project data was fragmented across 3 datasets (employees, seniority, projects) with missing values and inconsistent formats.

Task: Clean, transform, and integrate the datasets to build a reliable reporting framework.

Action:
Created and saved 3 dataframes (Employee, Seniority, Project) as .csv for downstream use.
Imputed missing project costs using a running average loop in Python.
Split employee names into first/last name and standardized gender-based prefixes.
Merged all datasets into a unified dataframe (Final) for analysis.
Automated designation updates: demoted employees on failed projects, promoted those aged 30+.
Engineered new metrics: bonus (5% of project cost on completions), total project costs per employee.
Filtered insights (e.g., employees from cities containing “o”).

Result: Delivered a clean, enriched dataset with automated rules for designation changes and cost tracking — demonstrating end-to-end data wrangling, feature engineering, and business rule application using Python (NumPy, Pandas).
