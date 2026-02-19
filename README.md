# Jayendra112233-Cricket-Player-Performance-DataAnalysis-In-all-Formats
This project focuses on analyzing cricket player performance across all major formats — Test, One Day Internationals (ODI), T20 Internationals, and Indian Premier League (IPL). The objective is to build a complete end-to-end data analysis that collects raw match data, transforms it into structured datasets, and generates meaningful insights.


# 🏏 End-to-End Cricket Data Analytics Project

**Using Web Scraping, Python, Pandas, SQLite & Power BI**

---

## 🔹 1️⃣ Data Scraping Using Selenium

🌐 **Website Used:** [https://cricsheet.org/matches/](https://cricsheet.org/matches/)
🛠 **Technologies:** Python + Sql + Power BI + Excel
🎯 **Objective:** Automate navigation and extract downloadable JSON match files.

### Match Types Extracted:

* Test Matches
* One Day Internationals (ODI)
* T20 Internationals
* Indian Premier League (IPL)

### Process:

* Automated browser interaction using Selenium
* Navigated match categories
* Extracted JSON file download links
* Downloaded structured match data programmatically

📌 **Key Learning:** Handling dynamic websites, automation, and scalable scraping.

---

## 🔹 2️⃣ Data Transformation & Cleaning

📚 **Library Used:** `pandas`
📂 **Input:** Raw JSON match files
📊 **Output:** Clean, structured DataFrames

### Process:

* Parsed nested JSON structures
* Flattened innings, deliveries, players, teams
* Created structured tables for:

  * Player performance
  * Team performance
  * Match metadata
* Standardized schema across formats
* Cleaned & extracted key fields:

  * Player name
  * Team
  * Runs
  * Wickets
  * Format
  * Match result
  * Venue

📌 **Key Learning:** Working with nested JSON and schema standardization.

---

## 🔹 3️⃣ Database Management

🗄 **Database:** SQLite
🛠 **Tools:** SQLAlchemy + sqlite3

### Tables Created:

* `test_matches`
* `odi_matches`
* `t20_matches`
* `ipl_matches`

### Task:

* Insert cleaned DataFrames into respective tables
* Maintain consistent schema across all formats
* Ensure relational integrity

📌 **Key Learning:** Database design and schema consistency

---

## 🔹 4️⃣ SQL Queries for Data Analysis

🧠 **Total Queries Written:** 42

### Insights Extracted:

* 🔝 Top 10 run-scorers by format
* 🎯 Leading wicket-takers by format
* 🏆 Team with highest win percentage in Test matches
* 💯 Count of centuries across all formats
* 🤏 Closest wins (smallest victory margins)
* 📊 Format-wise match statistics

📌 **Key Learning:** Aggregations, GROUP BY, window functions, performance insights.

---

## 🔹 5️⃣ Exploratory Data Analysis (Python)

📚 **Libraries Used:**

* matplotlib
* seaborn
* plotly

### 10+ Visualizations Created:

* Most runs by players
* Most wickets by players
* Format-wise run distribution
* Team performance comparison
* Match count by format
* Win percentage analysis


📌 **Key Learning:** Data storytelling & visual analytics.

---

## 🔹 6️⃣ Power BI Interactive Dashboard

Connected **Power BI** to SQLite database.

### Created 3 Interactive Dashboard Pages:

### 📊 1. Player Stats

* Top scorers
* Most matches played
* Batting averages

### 📈 2. Format Analysis

* Total runs by format
* Average wickets
* Match count per format

### 🏏 3. Team Insights

* Team performance comparison
* Win percentage
* Match distribution

### Features:

* Page navigation buttons
* Dynamic filtering by format
* Pie charts
* Bar charts
* Line charts
* Donut charts

📌 **Key Learning:** BI tools, dashboard interactivity, KPI storytelling.

---

# 🚀 Project Architecture Flow

```
Cricsheet Website
        ↓
Selenium Scraping
        ↓
Raw JSON Files
        ↓
Pandas Transformation
        ↓
SQLite Database
        ↓
SQL Analysis
        ↓
Python EDA
        ↓
Power BI Dashboard
        ↓
     Reports
```

---

# 🎯 Why This Project Is Strong for Interviews

This project demonstrates:

✅ Web Scraping
✅ Data Cleaning
✅ Data Modeling
✅ SQL Analytics
✅ Visualization
✅ BI Reporting
✅ End-to-End Pipeline Understanding

It shows you understand the **complete data lifecycle**.

---
