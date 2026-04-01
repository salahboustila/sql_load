# 📊 SQL Project: Data Analyst Job Market Analysis

## 🎯 Project Overview
This project is a deep dive into the modern job market for Data Analysts. Using a database of over 10,000 job postings, I built a **Star Schema** to analyze salary trends, high-demand skills, and the "Sweet Spot" where salary and job security meet.

## 🛠️ The Tech Stack
- **Database:** PostgreSQL
- **Tools:** VS Code, Git, GitHub
- **Concepts:** CTEs, Joins, Window Functions, Schema Design

## 🗄️ Database Architecture
I designed a professional-grade schema with the following core components:
- **`job_postings_fact`**: The central table containing salary, location, and job titles.
- **`skills_dim`**: A dimension table for all technical skills (Python, SQL, Tableau, etc.).
- **`companies_dim`**: Information on the organizations hiring for these roles.

## 🚀 Key Business Insights
- **The "Sweet Spot" Analysis:** Combined demand count and average salary to find the most valuable skills for remote Data Analysts.
- **Top 10 Paying Roles:** Identified the highest-earning remote positions in the current market.
- **Skill Demand:** Tracked the most frequent requirements for remote job postings.

## 📁 Repository Structure
- `1_create_database.sql`: SQL script to initialize the project.
- `2_create_tables.sql`: Script to define the Star Schema.
- `3_modify_tables.sql`: Commands for data updates and cleaning.# 📊 SQL Project: Data Analyst Job Market Analysis

## 🎯 Project Overview
This project is a deep dive into the modern job market for Data Analysts. Using a database of over 10,000 job postings, I built a **Star Schema** to analyze salary trends, high-demand skills, and the "Sweet Spot" where salary and job security meet.

## 🛠️ The Tech Stack
- **Database:** PostgreSQL
- **Tools:** VS Code, Git, GitHub
- **Concepts:** CTEs, Joins, Window Functions, Schema Design

## 🗄️ Database Architecture
I designed a professional-grade schema with the following core components:
- **`job_postings_fact`**: The central table containing salary, location, and job titles.
- **`skills_dim`**: A dimension table for all technical skills (Python, SQL, Tableau, etc.).
- **`companies_dim`**: Information on the organizations hiring for these roles.

## 🚀 Key Business Insights
- **The "Sweet Spot" Analysis:** Combined demand count and average salary to find the most valuable skills for remote Data Analysts.
- **Top 10 Paying Roles:** Identified the highest-earning remote positions in the current market.
- **Skill Demand:** Tracked the most frequent requirements for remote job postings.

## 📁 Repository Structure
- `1_create_database.sql`: SQL script to initialize the project.
- `2_create_tables.sql`: Script to define the Star Schema.
- `3_modify_tables.sql`: Commands for data updates and cleaning.
