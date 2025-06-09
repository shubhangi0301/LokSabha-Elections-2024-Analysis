# Lok Sabha Elections 2024 Analysis 🗳️

**🔍 Project Summary**  
This repository presents a polished data analysis pipeline built with **SQL (SSMS)** and **Power BI**, aimed to highlight my analytical proficiency as a data analyst (fresher). It examines the **Lok Sabha 2024** results at both state and constituency levels, focusing on alliance dynamics, vote margins, and seat distribution.

---

## 🚀 Tech Stack

- **SQL Server Management Studio (SSMS)** — Data cleaning, transformation, feature engineering  
- **Power BI Desktop** (.pbix) — Visualization, mapping, interactivity  
- **Files included**:
  - `SQL Queries.docx` – documentation of all SQL scripts
  - `.pbix` file – interactive dashboards
  - Any exported data in CSV/Excel formats (if added)

---

## 📊 SQL Analysis Scripts

All SQL scripts are documented in `SQL Queries.docx` and cover:

- **Total seats per state**
- **Seat counts by alliance**: NDA, INDIA, OTHER
- **Party-level seat counts** within alliances
- **Adding `party_alliance`** column and populating it for NDAs, INDIAs, Others
- **Alliance performance** summary across India and per state
- **Winner and runner-up** extraction with candidate details and vote margins
- **EVM vs Postal vote** comparisons
- **Top EVM vote-getters** per constituency
- **Candidate breakdown metrics** (e.g., in Maharashtra: seats, votes, number of parties/candidates)

These queries demonstrate:
- ✅ My ability to design analytical SQL workflows  
- ✅ Use of aggregations, window functions (`ROW_NUMBER()`), conditional columns, and joins  
- ✅ Formation of staging tables ready for reporting in Power BI

---

## 📈 Power BI Dashboard Highlights

The `.pbix` dashboard translates SQL outputs into:

- **Maps**: State-level and constituency-level color-coded by winning alliance or party  
- **Bar charts and tables**: Seat counts by alliance, top vote winners, margin distributions  
- **Drill-through** capabilities: Click on a state to explore its constituency-level details  
- **Tooltips & slicers**: For deep dive into candidates, vote shares, and alliance comparisons

---

## 🎯 What You’ll See

- **Alliance performance** visualized at national and state levels  
- **Seat-sharing breakdown**: NDA vs INDIA vs Others  
- **Margin analysis**: Identifying close races and blowout wins  
- **Vote-type insights**: EVM vs Postal votes across geographies  
- **Candidate rankings**: Top vote-getters and runner-ups per seat/state

---

## 📁 How to Explore

1. **Clone this repo**
2. **SQL**:
   - Run `.docx` SQL queries in SSMS to create your analysis tables.  
   - Export results to CSV/XLSX.
3. **Power BI**:
   - Open the `.pbix` file in Power BI Desktop.  
   - Update data sources to point to your exported files.
   - Interact with the visuals—use slicers for alliances, states, parties.

---

## 🧩 Why This Project Defines My Skills

- Demonstrates end-to-end **ETL** in SQL  
- Shows expertise in **data modeling and DAX** for complex measures  
- Highlights ability to build **insightful visual storytelling**  
- Emphasizes sensitivity to **political context** and **stakeholder needs**  
- Reflective of real-world data analyst responsibilities

---
