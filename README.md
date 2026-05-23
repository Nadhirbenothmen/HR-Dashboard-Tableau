<h1 align="center">Human Resources Analytics Dashboard</h1>

![Dashboard Banner](Dashboard.png)

An enterprise-grade HR Business Intelligence solution built to satisfy the comprehensive tracking needs of HR management. The platform delivers a dual-layered approach: a high-level **Summary View** for executive strategic insights and a granular **Employee Records View** for deep-dive operational analysis.

---

## 👤 User Story Objective
> **As an HR Manager**, I want a comprehensive dashboard to analyze human resources data, providing both summary views for high-level insights and detailed employee records for in-depth analysis.

---

## 🏗️ Project Development Roadmap
This project was designed and systematically engineered following a modular, container-based dashboard development process:

- [x] **Phase 1: Building Data Source** (Data extraction, transformation, modeling, and establishing HRIS connections)
- [x] **Phase 2: Building Charts** (Developing isolated baseline visualizations and correlation charts)
- [x] **Phase 3: Building Dashboards** (UI/UX layout integration and refinement)
    - [x] Plan the Dashboard
        - [x] Dashboard Mockup
        - [x] Container Mockup
    - [x] Create Container Structure
    - [x] Put All Together
    - [x] Fixing Colors
    - [x] Fix Texts
    - [x] Refine Charts
    - [x] Fix Spacing (Inner / Outer Padding)
    - [x] Fix Tooltips
    - [x] Add Filters & Legends
    - [x] Add Logos & Icons

---

## 📊 1. Summary View Dashboard
The summary view is engineered into three core functional modules to analyze institutional health, demographics, and compensation equity.

### 🔹 Overview Section
Provides a real-time health snapshot of core workforce pipelines and structural distribution.

* **Core KPIs:** * **Active Employees:** 7,984
  * **Hired Pipeline:** 8,950 
  * **Terminations:** 966
* **Historical Trends:** Dual timeline metrics track the total volume of hires (teal) and terminations (magenta) over time.
* **Organizational Breakdown:** Horizontal hierarchy tracking headcounts across **Departments** (led by *Operations* at 2,429 and *Sales* at 1,634) and structural **Job Titles**.
* **Geographic Distribution:** Maps headcounts across States (Illinois, Michigan, Ohio, Pennsylvania, New York) and isolates **Headquarters (New York at 70%)** vs. regional **Branches (30%)**.

### 🔹 Demographics Section
Delves into the baseline characteristics, background compositions, and capability matrices of the current talent pool.

* **Gender Representation:** Clean donut-chart tracking of the corporate gender ratio (**54% Male / 46% Female**).
* **Workforce Age & Education Grid:** A dual-axis dot matrix tracking headcount densities by matching age groups (`<25` through `55+`) directly against formal schooling milestones.
* **Volume Metrics:** Isolated visualization filters measuring overall totals per education level (**Bachelor** tracks as the highest volume cohort) and specific age brackets (**35-44** age range holds the majority).
* **Education & Performance Correlation:** A heat-grid tracking performance ratings (*Excellent, Good, Satisfactory, Needs Improvement*) against education. Notably, **50% of Bachelor-educated staff hold a "Good" performance tier**.

### 🔹 Income Analysis Section
Tracks total compensation statistics against employee profiles to identify pay equity trends and structural variances.

* **Gender & Education Pay Discrepancies:** Side-by-side compensation sliders pinpointing gender wage variances against educational backgrounds:

| Education Level | Female Average Salary | Male Average Salary |
| :--- | :--- | :--- |
| **High School** | \$63K | \$63K |
| **Bachelor** | \$66K | \$74K |
| **Master** | \$86K | \$80K |
| **PhD** | \$93K | \$80K |

* **Age, Salary, & Department Correlation:** A comprehensive scatter plot mapping individual salaries across age brackets. Interactive groupings allow users to hover and segment compensation models across corporate roles (e.g., *Finance Manager, IT Manager, Sales Specialist*).

---

## 🗂️ 2. Employee Records View
Designed for direct operational management and auditing, this granular reporting view enables users to view and query raw staff logs.

* **Comprehensive Master List:** Tabular structure hosting all verified employee attributes, including: Name, Assigned Department, Core Position/Job Title, Gender Identity, Age, Attained Education Level, and Base Salary.
* **Dynamic Query Filtering:** Built-in column-level logic allowing users to isolate, search, and slice the master list using any single or combination of available data columns.

---

## ⚙️ Interactive Features & UI/UX Standards

* **Container-Based Layout:** Built using strict spacing, padding guidelines, and a cohesive dark-mode design system to maximize scannability and cognitive clarity.
* **Global Filter Panel:** Sticky top navigation filters (`Gender`, `Status`, `Location`, `Hire Date`) to instantly subset data across all summary matrices.
* **Interactive Tooltips:** Custom context-rich hover cards configured across charts to display precise metrics without cluttering the canvas.

---

## 🛠️ Tools & Technologies Used
* **BI Platform:** Power BI / Tableau *(Edit based on your tool)*
* **Design Philosophy:** Container-based modular UI layout
* **Data Concepts:** ETL (Extract, Transform, Load), Data Modeling, Row-Level Filtering

---
*Note: This repository contains mocked corporate data used for structural visualization and BI portfolio purposes only.*
