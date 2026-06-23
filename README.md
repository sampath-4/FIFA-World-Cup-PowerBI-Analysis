# ⚽ FIFA World Cup (1930-2022): 22 Editions of Football History

## 📊 Project Overview
This repository hosts an end-to-end Power BI data analytics project that visualizes the historical evolution, scale, and performance metrics across all 22 editions of the FIFA World Cup. 

Rather than just displaying basic operational metrics, this project was built to showcase modern business intelligence principles: a high data-to-ink ratio, strict UI/UX visual hierarchy, explicit DAX data modeling, and clean interactive data storytelling.

---📸 Dashboard Preview
[FIFA World Cup Dashboard](dashboard.png)

## 💡 Key Analytical Insights Delivered
* **The "Host Advantage" Fact-Check:** A dedicated breakdown reveals that host nations have only won the tournament 27% of the time (6 out of 22 editions), proving that home soil does not guarantee a championship.
* **Goal Efficiency Trends:** While the overall scale of the tournament (teams and matches) has grown significantly over the decades, the average goals scored per match peaked drastically in 1954 (5.38 goals) and has since stabilized to a lower, defense-heavy modern baseline.
* **Historical Attendance Demands:** Visualizes the massive stadium scaling over time, highlighting how modern tournaments cross multi-million cumulative fan benchmarks.

---

## 🛠️ Tech Stack & Technical Implementation

### 1. Data Cleaning & Engineering (Power Query)
* Profiled the dataset to handle missing values, regional naming conventions, and structural data anomalies.
* Configured proper data formatting types for timestamps, geographical attributes, and metric fields to ensure accurate sorting.
* Handled full-name resolution for historical entities (e.g., ensuring legendary top scorers like **Just Fontaine** and modern stars like **Kylian Mbappé** are fully accounted for without string truncation errors).

### 2. Analytical Architecture & Visual Layout
The single-page executive dashboard is meticulously structured into a logical reading grid:
* **Executive Summary (Top Row):** Clean, high-impact Callout Cards summarizing total tournaments, goals, historical attendance, and averages.
* **Trend & Proportional Analytics (Middle Row):** A dual-axis line/area chart tracking average goals over time alongside a proportional donut chart tackling the host win-rate distribution.
* **Deep Dives & Dominance Matrices (Bottom Row):** Bar charts identifying top-performing historical scorers and tracking cumulative attendance growth, alongside a breakdown ranking championships won by country.

### 3. Data Modeling & DAX Engineering
* Developed a clean, high-performance data layout instead of working out of a flat table.
* Wrote explicit, scalable DAX measures for aggregations, distinct metrics, and conditional logic ratios—avoiding reliance on default implicit columns.

---
*Developed as a professional portfolio asset to demonstrate corporate-ready data modeling, UI/UX execution, and interactive reporting.*
