🍕 Pizza Sales Analytics Dashboard
📘 Overview

The Pizza Sales Analytics Dashboard is a business intelligence project built using Power BI to analyze pizza sales performance and uncover data-driven insights.
This interactive dashboard provides a detailed view of sales trends, top-performing products, category analysis, and customer behavior, enabling decision-makers to enhance sales strategies and operational efficiency.

🎯 Objective

To transform raw transactional data into actionable insights through intuitive and interactive visualizations, supporting data-driven decision-making in the food retail industry.

📊 Key Features

Comprehensive Sales KPIs:
Displays Total Revenue, Total Pizzas Sold, Total Orders, and Average Order Value.

Category and Size Analysis:
Evaluates sales performance across pizza categories (Classic, Supreme, Veggie, Chicken) and sizes (Small to Extra Large).

Trend Visualization:
Tracks daily and monthly sales performance to identify peak demand periods.

Top & Bottom Performer Analysis:
Highlights best and worst-selling pizzas by revenue, quantity, and order volume.

Dynamic Interactivity:
Interactive filters for date range, pizza category, and size — enhancing user exploration and insight discovery.

💡 Key Insights

Classic pizzas generated the highest revenue share among all categories.

Large size pizzas were the most preferred by customers.

Thursday and Friday evenings recorded peak sales activity.

Thai Chicken Pizza achieved the highest revenue, while Pepperoni Pizza had the most orders.

Spinach Pizza and Soppresatta Pizza showed consistently low sales, indicating scope for menu optimization.

🧰 Tools & Technologies Used
Tool / Technology	Purpose
Power BI	Data visualization and report development
Power Query	Data extraction, cleaning, and transformation
DAX (Data Analysis Expressions)	Calculations for KPIs and measures
Microsoft Excel / CSV	Data source and pre-processing
📸 Dashboard Preview
🔹 Page 1 – Sales Overview

Displays key KPIs, daily order trends, category & size-wise sales performance.


🔹 Page 2 – Top & Bottom Performers

Showcases the best and least performing pizzas by revenue, quantity, and orders.


🧮 Sample DAX Measures
-- Total Revenue
Total Revenue = SUM('Pizza_Sales'[Total_Price])

-- Total Orders
Total Orders = DISTINCTCOUNT('Pizza_Sales'[Order_ID])

-- Average Order Value
Avg Order Value = [Total Revenue] / [Total Orders]

-- Total Quantity Sold
Total Quantity = SUM('Pizza_Sales'[Quantity])

📁 Project Structure
📦 Pizza_Sales_Analytics_Dashboard

 📊 Pizza_Sales_Report.pbix
 
 📈 pizza_sales_data.csv

 🖼️ snapshot of Pizza analytics dashboard 1.png
 
 🖼️ snapshot of Pizza analytics dashboard 2.png
 
 📘 README.md

🚀 How to Use

Download the repository files or clone it using Git:

git clone https://github.com/yourusername/Pizza-Sales-Analytics-Dashboard.git


Open the .pbix file in Power BI Desktop.

Load the dataset (pizza_sales_data.csv).

Explore the dashboard using interactive filters and visuals.

📈 Business Impact

This dashboard empowers stakeholders to:

Identify top-performing products and low-performing pizzas.

Optimize menu offerings and pricing strategies.

Improve sales forecasting and inventory planning.

Enhance marketing decisions with insights on peak demand days and customer preferences.

👨‍💻 Developer

Author: Rahul N
Role: Data Analyst | Power BI Developer
LinkedIn: [Your LinkedIn Profile URL]
GitHub: [Your GitHub Profile URL]
