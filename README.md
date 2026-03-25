# Data Science Jobs Dashboard

An interactive Tableau dashboard analyzing data science job salaries across roles, experience levels, employment types, and geographies from 2020 to 2022.

## Overview

This project visualizes global data science compensation trends using a dataset of 607 job records. It helps job seekers, hiring managers, and researchers understand how salaries vary by role, experience, company size, and remote work ratio.

## Dashboard

The dashboard is built in Tableau and packaged as `Data science jobs Dashboard.twbx`. Open it with **Tableau Desktop** or **Tableau Public** (free).

### Key Insights Covered

- Salary distribution by job title (Data Scientist, ML Engineer, Data Analyst, etc.)
- Compensation trends over time (2020–2022)
- Experience level breakdown: Entry, Mid, Senior, Executive
- Employment type: Full-time, Part-time, Contract, Freelance
- Remote work ratio impact on salary
- Company size comparison (Small, Medium, Large)
- Geographic breakdown by employee residence and company location

## Dataset

**File:** `ds_salaries.csv`
**Records:** 607 rows
**Source:** [ai-jobs.net Salaries](https://ai-jobs.net/salaries/)

### Columns

| Column | Description |
|---|---|
| `work_year` | Year the salary was reported (2020–2022) |
| `experience_level` | EN (Entry), MI (Mid), SE (Senior), EX (Executive) |
| `employment_type` | FT (Full-time), PT (Part-time), CT (Contract), FL (Freelance) |
| `job_title` | Job role (e.g., Data Scientist, ML Engineer) |
| `salary` | Gross salary in local currency |
| `salary_currency` | ISO 4217 currency code |
| `salary_in_usd` | Salary converted to USD |
| `employee_residence` | Employee's country (ISO 3166 code) |
| `remote_ratio` | % of remote work: 0 (on-site), 50 (hybrid), 100 (fully remote) |
| `company_location` | Company's country (ISO 3166 code) |
| `company_size` | S (Small <50), M (Medium 50–250), L (Large >250) |

## Getting Started

1. Install [Tableau Desktop](https://www.tableau.com/products/desktop) or [Tableau Public](https://public.tableau.com/app/discover)
2. Clone or download this repository
3. Open `Data science jobs Dashboard.twbx` in Tableau
4. The CSV data is embedded in the `.twbx` file — no additional setup needed

## Tools Used

- **Tableau** — Dashboard design and data visualization
- **CSV Dataset** — Raw salary data for 2020–2022
