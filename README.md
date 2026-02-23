# Furniture Sales Performance Analysis

## 🛋️ Dashboard Preview
![Furniture Sales Dashboard](furniture_sales_preview.png)

## 📌 Project Overview
This project focuses on analyzing the sales data of a furniture retail business. By visualizing sales across different categories (Chairs, Tables, Sofas, etc.), the dashboard helps stakeholders identify high-margin products and geographical regions with the highest growth potential.

## 🛠️ Technical Implementation
* **Data Modeling:** Developed a robust data model with relationships between Sales, Products, and Geography tables.
* **DAX Calculations:** Created key measures for:
  * **Total Sales & Profit:** `SUM(Sales[Amount])` and `SUM(Sales[Profit])`.
  * **Profit Margin %:** `DIVIDE([Total Profit], [Total Sales], 0)`.
  * **Year-to-Date (YTD) Sales.**
* **Visualizations:** Used Tree Maps for category distribution, Map visuals for regional sales, and Line Charts for seasonal trend analysis.

## 💡 Business Insights
* **Top Performers:** Identified the furniture sub-categories that contribute most to the total revenue.
* **Regional Analysis:** Highlighted which states/regions are underperforming to suggest targeted marketing campaigns.
* **Profitability:** Noted a correlation between discount levels and overall profit margins.

## Tools Used
* **Power BI Desktop**
* **DAX (Data Analysis Expressions)**
* **Power Query**
