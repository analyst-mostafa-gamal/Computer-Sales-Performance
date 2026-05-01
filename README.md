# Computer Sales Performance Dashboard

<img width="1286" height="726" alt="Screenshot 2026-05-01 031825" src="https://github.com/user-attachments/assets/4613cbec-99b9-4067-8cdf-4d17886e789f" />

## 📌 Project Overview
This project features an interactive Power BI Dashboard that provides a comprehensive analysis of computer hardware and mobile sales performance. By processing over 40,000 records from the Computer.xlsx dataset, the dashboard delivers actionable insights into revenue trends, regional performance, and salesperson efficiency.  

## ⚙️ Technical Approach
- **Data Source:** **Computer.xlsx**, containing detailed transaction logs including Order Dates, Regions, Product Categories, and Sales Rep data.

- **ETL Process:** Data was cleaned and transformed using Power Query, including the creation of calculated columns for Profit and Profit Margin.

- **Advanced DAX:** Implemented measures for:

  - **Total Sales & Profit:** Dynamic aggregation across different dimensions.

  - **AOV (Average Order Value):** Calculated at **8.33K**.

  - **Year-over-Year Comparisons:** To track performance dips and peaks.
 
- **Data Visualization:**

  - **Line Charts:** For temporal sales trends.

  - **Donut Charts:** For payment method and regional profit distribution.

  - **Bar & Column Charts:** To rank product names and salesperson performance.

 ## 🛠️ Tools & Technologies
- **Power BI Desktop:** For data modeling and visualization.  
- **Power Query:** For ETL (Extract, Transform, Load) processes and data cleaning.
- **DAX (Data Analysis Expressions):** For calculated columns and measures.

## 📊 Key Insights
Based on the dashboard analysis:

- **Total Financials:** The business generated **333.27M** in Total Sales with **a high Profit Margin of 87.25%**, resulting in **290.80M** in Total Profit.

- **Sales Trends:** While sales were robust in 2023 **(165M)** and 2024 **(167M)**, there is a sharp decline noted for the start of 2025 **(1M)**, indicating a need for early-year strategic pivots.

- **Regional Consistency:** Sales are remarkably balanced across Egypt, with **Cairo** leading **(68M)**, closely followed by Aswan, Giza, Alexandria, and Mansoura (each around **66-67M**).

- **Product Performance:** **Mobiles** and **Laptops** are the top revenue drivers, each contributing **112M** to total sales.

- **Top Talent:** **Robert Greene** is the leading Sales Representative, contributing **16.7M** in sales and managing over **2.1K** orders.
