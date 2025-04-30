# 📊 Global Terrorism Analysis Dashboard (2000–2017)

This repository contains a comprehensive Tableau dashboard project focused on analyzing terrorism incidents in India from the year 2000 to 2017. The aim of this project is to uncover patterns, trends, and critical insights that can assist policymakers, analysts, and researchers in understanding the nature and evolution of terrorism over time.

---

## 🧹 Data Cleaning & Preparation

Before visualization, significant preprocessing steps were conducted to ensure data integrity and relevance:

- ✅ **Data Cleaning**: Removed missing values, duplicates, and inconsistent entries to maintain accuracy.
- 📅 **Date Formatting**: Merged `year`, `month`, and `day` columns into a single standardized date field for better time-series analysis.
- 🧾 **Field Selection**: Chose only the relevant columns to focus the analysis. These included:
  - Country
  - Region
  - State / City
  - Attack Type
  - Target Type
  - Weapon Type
  - Number of Fatalities & Injuries
  - Terrorist Group Name
- 📥 **CSV Export**: Final cleaned dataset was exported in `.csv` format and then imported into Tableau for visualization.

---

## 📈 Dashboard Features

The dashboard was designed using Tableau with a focus on clarity, interactivity, and business intelligence best practices. It includes:

### 🎯 Key Performance Indicators (KPIs)
- **Total Fatalities**
- **Total Injuries**
- **Total Number of Attacks**

### 📍 Geographical Insights
- **State-wise Attack Distribution**: Horizontal bar chart ranking states by attack count.
- **Casualty Analysis by Top Cities**: Bubble chart showing cities with the highest casualties.

### 🔍 Attack Analysis
- **Attack Type Distribution**: Bar chart detailing the most common types of attacks.
- **Weapon Type Usage**: Treemap visualizing frequency of weapon types.
- **Top Terrorist Groups**: Bar chart of groups responsible for the most attacks.
- **Yearly Attack Trends**: Line chart comparing trends in top attack types over the years.

### 🔄 Interactivity
- Drop-down filters for:
  - Attack Type
  - Target Type
  - Year
  - Terrorist Group

---

## 🛠️ Tools & Technologies

| Tool      | Purpose                     |
|-----------|-----------------------------|
|  Python** | Data Cleaning & Preprocessing |
| **Tableau desktop 2025.1** | Interactive Dashboard Creation |
| **CSV** | Final cleaned dataset format |

---

## 📂 File Summary

- `terrorism_data_cleaned.csv` – Cleaned dataset used for visualization  
- `Global_Terrorism_Dashboard.twbx` – Final Tableau dashboard  
- `README.md` – Project documentation

---

## 📌 Project Objective

To build a powerful, interactive, and insight-driven dashboard that helps in understanding:

- Which states and cities are most affected by terrorism?
- What are the most commonly used attack and weapon types?
- Which terrorist groups were most active during the period?
- How has the frequency of attacks changed over time?

---

## ✅ Outcome

This dashboard offers a data-driven lens into terrorism activity across India, empowering decision-makers with actionable intelligence and trends.

---

> 📁 **Note**: This project was created as part of a data analytics and visualization learning program. All data used is publicly available.

