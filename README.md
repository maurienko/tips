# 🍽️ Customer Tipping Patterns: An Exploratory and Dashboard Analysis



**Live Dashboard**: https://www.figma.com/make/qDUbokTrsegeW3kknC7OQ8/User-Dashboard?node-id=0-4&t=AODOZUAm9vPCNpqP-1

---

## 💡 Overview

This project analyzes restaurant tipping data to identify the key features influencing tip percentage. We moved from initial data exploration and feature engineering in **SQL (BigQuery)** to a final, interactive dashboard for presenting actionable business insights.

**Primary Objective:** To statistically determine which customer and service factors (e.g., party size, day, sex) have the most significant impact on the percentage of the bill left as a tip.

---

## 🔑 Key Findings (Actionable Insights)

The analysis uncovered clear drivers of tipping behavior:

| Factor | Insight | Mean Tip % (Highlight) |
| :--- | :--- | :--- |
| **Party Size** | **Most Significant Driver:** Smaller groups (size 1) tip substantially higher. Tip percentage generally drops as size increases. | **21.73%** (Size 1) |
| **Day** | **Friday** sees the highest average tip percentage, while Saturday is the lowest. | **16.99%** (Friday) |
| **Gender** | Female customers tip slightly more generously on average than male customers. | **16.65%** (Female) |
| **Time** | Lunch service shows a slightly higher tip percentage than Dinner. | **16.41%** (Lunch) |

---

## 🛠️ Technical Stack

| Component | Tool / Language | Purpose |
| :--- | :--- | :--- |
| **Data Storage / Querying** | **Google BigQuery** | Initial data loading, cleaning, and calculating the core metric (`tip_percentage`). |
| **Exploratory Analysis (EDA)** | **SQL (BigQuery Standard)** | Used `GROUP BY` and `AVG()` to summarize tipping behavior across all categories. |
| **Visualization / Dashboard** | **Figma** (or Power BI) | Creation of the final, interactive, and shareable executive dashboard. |

---

## 🗺️ Project Structure

* **`sql_scripts/`**: Contains the BigQuery SQL files used for cleaning the data and generating the aggregate tables for analysis.
* **`data/`**: Holds the final cleaned dataset (e.g., `tips_with_percentage.csv`) used to build the dashboard.
* **Live Dashboard Link**: https://www.figma.com/make/qDUbokTrsegeW3kknC7OQ8/User-Dashboard?node-id=0-4&t=AODOZUAm9vPCNpqP-1

---

## 🧑‍💻 Connect

* **Author:** Mariia
* **LinkedIn:** www.linkedin.com/in/maurienko
