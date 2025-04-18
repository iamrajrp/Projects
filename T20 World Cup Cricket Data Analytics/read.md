# 🏏 T20 Dream Team Builder & Player Analytics Dashboard

An end-to-end **data analytics project** that helps build and analyze an ideal T20 Dream11 team using actual performance data. Designed to mirror enterprise-level analytics workflows, the project spans from **data acquisition to business-ready insights** via an interactive Power BI dashboard.

## 📈 The Data Journey

This project follows a complete **ETL (Extract, Transform, Load)** data pipeline:

### 🔍 Extract
- Web scraped raw T20 player data from [ESPNcricinfo](https://www.espncricinfo.com) using Python for multiple player categories (batting, bowling, all-rounders).
- Scraped stats included: batting average, strike rate, innings, boundary %, balls faced, bowling economy, and more.

### 🧹 Transform
- Parsed and cleaned scraped data:
  - Removed null/incomplete records
  - Normalized formats (e.g., converting strings to floats, dates, percentages)
  - Applied domain-specific filters (e.g., minimum innings criteria, position filters based on role)
- Engineered new columns and metrics like:
  - Batting Position tags
  - Aggregated performance metrics
  - Categorization into Openers, Middle Order, Finishers, All-Rounders, and Bowlers
- Exported transformed datasets into `.csv` files

### 📦 Load & Visualize
- Imported structured CSV files into **Power BI**
- Created role-based tabs and interactive views using:
  - **Bar Charts** (for runs, averages)
  - **Scatter Plots** (strike rate vs average)
  - **KPI Cards** (aggregated stats)
  - **Line Charts** (performance trends over time)
- Built dynamic selection logic to allow combining player stats and projecting team performance using **DAX measures** and **calculated columns**

---

## 🧠 Project Goals
- Simulate a stakeholder-style problem-solving approach
- Showcase full-cycle data analytics skills: **data acquisition, transformation, modeling, and visualization**
- Demonstrate ability to deliver meaningful, self-serve insights through interactive dashboards

## 🛠️ Technologies Used
- Python (`pandas`)
- SQL (for logical filtering and transformations)
- Power BI (visualization, interactivity)
- DAX (calculated fields, KPIs)

---

> 🎯 This project demonstrates how raw, unstructured web data can be turned into actionable insights — exactly the kind of analytical thinking and technical workflow expected from a Data Analyst in a real-world setting.

