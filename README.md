
🍫 Awesome Chocolate Sales Dashboard – Power BI

A beautifully designed and interactive Power BI dashboard that analyzes chocolate sales performance across regions, products, and time. This report helps businesses understand trends, identify top-performing items, monitor KPIs, and make data-driven decisions.


---

📊 Project Overview

The Awesome Chocolate Dashboard provides a complete view of:

✔ Sales performance

✔ Profit and revenue trends

✔ Top products and categories

✔ Region-wise and city-wise performance

✔ Monthly and yearly growth

✔ Customer insights

✔ Inventory & supply indicators


This dashboard is created using Power BI Desktop, designed for clarity, performance, and decision-making.


---

🧾 Features

🔹 1. Sales Summary KPIs

Total Sales

Total Profit

Average Order Value

Total Quantity Sold

YoY Growth Indicator


🔹 2. Trend Analysis

Sales trend by month & year

Seasonal performance patterns

Profit trend over time


🔹 3. Product Insights

Top 5 Best-Selling Chocolates

Category-wise performance

SKU contribution to revenue


🔹 4. Region & Store Performance

Region-wise comparison

City-wise sales mapping

Store-level performance metrics


🔹 5. Interactivity

Slicers for date, category, region

Dynamic visual interactions

Clean and responsive layout



---

🛠 Tools & Technologies Used

Tool	Purpose

Power BI Desktop	Visualization & Dashboard Creation
Power Query	Data Cleaning & ETL
DAX	Calculated Columns & Measures
Excel / CSV	Data Source
GitHub	Version Control & Sharing


---

📐 DAX Measures Used (Examples)

Total Sales = SUM(Sales[SalesAmount])

Total Profit = SUM(Sales[Profit])

YoY Growth % =
DIVIDE(
    [Total Sales] - CALCULATE([Total Sales], DATEADD(Date[Date], -1, YEAR)),
    CALCULATE([Total Sales], DATEADD(Date[Date], -1, YEAR))
)


---

🚀 How to Use

1. Download the .pbix file


2. Open in Power BI Desktop


3. Update the data source if required


4. Explore the interactive visuals


5. Modify the visuals and publish to Power BI Service




---

🤝 Contributions

Contributions, feedback, and suggestions are welcome!
Feel free to open a Pull Request or Issue.


---


✅ Add badges (Power BI • GitHub • License)

Just tell me!
