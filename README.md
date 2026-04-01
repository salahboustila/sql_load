# 📊 SQL & Data Visualization Project: Job Market Analysis

## 🎯 Project Overview
This project is a comprehensive analysis of the modern job market for Data Analysts. Utilizing a massive dataset of **780,000+ job postings**, I built a robust **PostgreSQL Star Schema** to uncover salary trends and identify the "Sweet Spot" where high compensation meets high job security.

## 🛠️ The Tech Stack
- **Database:** PostgreSQL (Advanced SQL)
- **Data Visualization:** Python (Matplotlib) & **Tableau**
- **Tools:** VS Code, Git/GitHub

## 🚀 Key Business Insights
- **The "Sweet Spot":** Specialized roles like **Data Architect** command the highest average salary at **$157,555**.
- **Remote Advantage:** Remote Data Analyst positions show an average salary of **$93,346**, which is roughly **$6,500 higher** than non-remote counterparts ($86,760).
- **Seniority Premium:** Moving from a "Junior" role ($63k) to a "Lead" role ($113k) represents an **80% increase** in earning potential.

## 📈 Visualizations

### 1. The "Sweet Spot" (Salary vs. Demand)
This scatter plot identifies which job titles fall into the "High Salary / High Demand" quadrant.
![Sweet Spot Analysis](assets/sweet_spot_analysis.png)

### 2. Salary Distribution by Title
A ranking of the top 10 highest-paying roles from the dataset.
![Salary Distribution](assets/avg_salary_by_title.png)

### 3. Interactive Tableau Dashboard
I am developing an interactive dashboard to allow for dynamic filtering of these job trends.
**[👉 View Interactive Tableau Dashboard](#)** *(Paste your link here later)*

## 📁 Repository Structure
- `1_create_database.sql`: SQL script to initialize the project environment.
- `2_create_tables.sql`: Script defining the Star Schema architecture.
- `3_modify_tables.sql`: Data ingestion (`COPY` commands) and cleaning.
