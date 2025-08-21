## 🐍 Capstone Project – Python Fundamentals (by Skillovilla)

### 📌 Project Overview

This project focused on consolidating fragmented employee and project-related datasets into a **clean, reliable reporting framework**. The objective was to handle **data cleaning, transformation, feature engineering, and business rule automation** using core Python fundamentals.

---

### 🔎 Key Insights & Actions

📂  **Data Integration:** 
* Combined 3 fragmented datasets (**Employees, Seniority, Projects**) into a unified reporting structure after handling missing values and inconsistent formats.

🔧   **Data Cleaning & Standardization:**

  * Split employee names into **first/last names** and standardized **gender-based prefixes**.
  * Imputed missing project costs using a **running average loop**.

⚙️ **Business Rule Automation:**

 * **Designation Updates:** Automated promotions (employees aged 30+) and demotions (on failed projects).
 * **Bonus Calculations:** Engineered bonus metric = **5% of project cost on completions**.
 * Tracked **total project costs per employee** for financial insights.

📊 **Analytical Insights:**

 * Filtered subsets, e.g., **employees from cities containing “o”**, demonstrating advanced querying capabilities.

---

### ⚙️ Technologies Used

 * **Language:** Python
 * **Libraries:** NumPy, Pandas
 * **Data Storage:** CSV (Employee, Seniority, Project, Final Unified Dataset)

