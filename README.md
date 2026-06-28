# live_project_1
# Bangalore Tech Salary Decoder

A comprehensive salary intelligence analysis project built using Python and Pandas on a dataset of 1,015 Bengaluru technology professionals.

## Overview

This project analyzes compensation trends across the Bengaluru technology ecosystem by studying the impact of:

* Job Roles
* Years of Experience
* Company Type
* Technical Skills
* Education Tier
* Salary Premiums

The objective is to uncover meaningful patterns in salary distributions and generate actionable insights for students, job seekers, recruiters, and professionals.

---

## Project Objectives

The project answers five major business questions:

### Q1. CTC Distribution by Role

Compute:

* Median Salary
* Mean Salary
* Minimum Salary
* Maximum Salary

Identify:

* Highest paying role
* Lowest paying role
* Salary outliers

---

### Q2. Experience Curve for SDE Backend

Analyze salary growth for Backend Engineers using experience bands:

* 0–1 Years
* 2–3 Years
* 4–5 Years
* 6+ Years

Determine how compensation evolves with experience.

---

### Q3. Skill Premium Analysis

Compare salary premiums for:

* AWS
* Machine Learning
* System Design
* Kubernetes

Evaluate which technical skills contribute the most toward higher compensation.

---

### Q4. Company-Type Premium

Compare salaries among:

* Unicorn Companies
* MNCs
* Mid-size Companies
* Early-stage Startups

Measure the salary premium offered by Unicorn companies over MNCs for similar roles.

---

### Q5. Underpaid Professionals

Identify professionals whose salaries are significantly below the median compensation of peers having:

* Similar Role
* Similar Experience
* Similar Company Type

This helps reveal potential compensation disparities.

---

## Dataset Information

Dataset Name

```text
bangalore_tech_salaries.csv
```

Records

```text
1015
```

Features

```text
Employee_ID
Role
Years_Experience
Current_CTC
Previous_CTC
Company
Company_Type
Skills
Education_Tier
Work_Mode
Location
Joining_Year
```

Salary values are intentionally stored in multiple formats:

```text
15.5 LPA

15.5

15,50,000

₹15.5 LPA
```

The project includes custom parsing logic to standardize these values into LPA.

---

## Technologies Used

Python

Pandas

NumPy

Jupyter Notebook

Google Colab

GitHub

---

## Project Workflow

### Step 1 — Data Inspection

* Dataset Shape
* Data Types
* Missing Values
* Duplicate Records
* Summary Statistics

---

### Step 2 — Data Cleaning

Performed:

* Column standardization
* Salary parsing
* Duplicate removal
* Role normalization
* Company category cleaning
* Education tier cleaning

---

### Step 3 — Exploratory Analysis

Implemented:

* GroupBy Analysis
* Aggregations
* Experience Segmentation
* Skill Comparison
* Salary Benchmarking
* Gap Analysis

---

### Step 4 — Salary Intelligence Report

Generated a formatted salary report including:

* Median Salary by Role
* Experience Curve
* Skill Premiums
* Company Premiums
* Underpaid Professionals

---

## Major Findings

### Highest Paying Role

Product Manager

Median Salary:

```text
31.6 LPA
```

---

### Lowest Paying Role

Data Analyst (DA)

Median Salary:

```text
15.9 LPA
```

---

### Backend Salary Growth

```text
0–1 Years  → 14.1 LPA

2–3 Years → 19.95 LPA

4–5 Years → 25.8 LPA

6+ Years → 40.2 LPA
```

---

### Skill Premium

```text
AWS              +21.84%

ML               +3.04%

System Design    +29.90%

Kubernetes      -18.06%
```

---

### Company Premium

```text
Unicorn      26.4 LPA

MNC          19.95 LPA

Premium      +32.33%
```

---

## Key Insights

### Insight 1

Product Manager roles command the highest compensation with a median salary of **31.6 LPA**, nearly double that of Data Analysts.

Students interested in maximizing compensation should consider product-focused career paths.

---

### Insight 2

Backend salaries grow from **14.1 LPA** to **40.2 LPA** after six years of experience, demonstrating strong long-term earning potential.

Developing deep backend expertise can significantly improve career growth.

---

### Insight 3

System Design contributes the largest skill premium at **29.9%**, followed by AWS at **21.84%**.

Students targeting Software Engineering positions should prioritize System Design and Cloud technologies.

---

## Repository Structure

```text
Bangalore-Tech-Salary-Decoder/

│

├── bangalore_tech_salaries.csv

├── Salary_Decoder.ipynb

├── README.md

└── images/
```

---

## Learning Outcomes

Through this project I learned:

✔ Data Cleaning

✔ Salary Parsing

✔ Feature Engineering

✔ GroupBy Operations

✔ Business Analytics

✔ Exploratory Data Analysis

✔ Salary Benchmarking

✔ Report Generation

✔ Python Data Analysis

✔ Pandas Aggregations

---

## Author

Sri Sai Nandini

B.Tech Artificial Intelligence and Data Science

Amrita Vishwa Vidyapeetham

---

