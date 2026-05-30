# Human-Resources-Dashboard-

## Table of Contents
1. [Project Overview](#1-project-overview)
2. [Business Problem](#2-business-problem)
3. [Project Objectives](#3-project-objectives)
4. [Project Tools](#4-project-tools)
5. [Repository Structure](#5-repository-structure)
6. [Dataset Overview](#6-dataset-overview)
7. [Dashboard Overview](#7-dashboard-overview)
8. [Dashboard Screenshots](#8-dashboard-screenshots)
9. [Key Insights](#9-key-insights)
10. [Recommendations](#10-recommendations)
11. [Assumptions & Limitations](#11-assumptions--limitations)
12. [Future Enhancements](#12-future-enhancements)
13. [Author](#13-author)

## 1. Project Overview
The Human Resource Dashboard is an interactive Tableau analytics solution designed to provide comprehensive insights into workforce composition, employee demographics, compensation trends, and organizational performance.

The project enables HR teams and business stakeholders to monitor workforce growth, analyze employee distribution, identify salary trends, and explore detailed employee records through dynamic visualizations and filtering capabilities.

The solution consists of:

- Summary Dashboard
- Details Dashboard

## 2. Business Problem
Organizations generate large volumes of HR data across departments, employee groups, and locations. Without centralized analytics, gaining clear visibility into workforce trends, employee demographics, compensation patterns, and workforce distribution becomes challenging. This can limit the ability to effectively monitor workforce changes, evaluate organizational structure, identify potential pay disparities, and access employee information efficiently.

This dashboard addresses these challenges by transforming raw HR data into interactive and actionable business insights that support workforce analysis and decision-making.

## 3. Project Objectives
This project aims to develop a centralized HR analytics dashboard that provides visibility into workforce trends, employee demographics, compensation patterns, and organizational distribution. The dashboard is designed to support data-driven HR decision-making by enabling analysis of hiring and termination trends, salary distribution, and employee-level insights across departments and locations.

## 4. Project Tools

* **Tableau** — Dashboard development, data visualization, and interactive reporting
* **CSV Dataset** — Source data used for workforce analysis and dashboard creation
* **Python Faker Library** — Synthetic HR dataset generation
* **ChatGPT** — Assisted with dataset structure planning and project documentation
* **Git & GitHub** — Version control and project documentation management

## 5. Repository Structure
```text
Human-Resources-Dashboard/
│
├── dashboard/
│   └── hr-dashboard
│
├── data/
│   └── dataset
│
├── docs/
│   ├── business-requirements.md
│   └── insights-report.md
│
├── images/
│   ├── details.jpg
│   └── summary.jpg
│
├── scripts/
│   └── generate_data.py
│
├── LICENSE
└── README.md
```

## 6. Dataset Overview

The dataset used for this project is a synthetic Human Resource dataset containing employee records related to demographics, departments, job roles, salaries, education levels, employment status, and performance ratings.

The dataset was generated using ChatGPT and the Python Faker library. It supports workforce analysis across several key areas, including hiring and termination trends, employee demographics, salary distribution, departmental performance, and geographic workforce distribution.

## 7. Dashboard Overview

### Summary Dashboard
The Summary Dashboard is divided into three analytical sections:

#### Overview
Provides high-level workforce KPIs including:
- Total hired employees
- Active employees
- Terminated employees
- Hiring vs termination trends
- Department distribution
- Geographic employee distribution

#### Demographics
Analyzes workforce composition including:
- Gender distribution
- Age group analysis
- Education level distribution
- Education vs performance relationship

#### Income 
Focuses on compensation insights including:
- Salary comparison by education and gender
- Age vs salary
  
### Details Dashboard
Provides a detailed employee directory with:
- Interactive filtering
- Employee-level drill-down analysis
- Workforce exploration by department, education, gender, and salary

## 8. Dashboard Screenshots

### Summary Dashboard
![Summary Dashboard](Images/Summary.jpg)

### Details Dashboard
![Details Dashboard](Images/Details.jpg)

## 9. Key Insights
