🛒 Blinkit Sales Analysis Dashboard
📌 Project Overview

The Blinkit Sales Analysis Dashboard is an interactive Business Intelligence project developed using Python, Excel, Jupyter Notebook, and Microsoft Power BI. The project focuses on analyzing Blinkit's sales data to uncover meaningful business insights related to revenue, customer behavior, payment methods, delivery performance, and sales trends.

The raw dataset was cleaned, transformed, and analyzed using Python before being visualized in Power BI through an interactive dashboard.

🎯 Objectives
Analyze overall business performance.
Monitor revenue trends across different months.
Compare yearly sales performance (2023 vs 2024).
Identify customer purchasing patterns.
Evaluate delivery performance.
Analyze preferred payment methods.
Build an interactive dashboard for business decision-making.
🛠️ Tools & Technologies Used
Python
Jupyter Notebook
Pandas
NumPy
Matplotlib
Microsoft Excel
Microsoft Power BI
Git & GitHub
📂 Dataset Information

The dataset contains sales information including:

Order ID
Customer ID
Product ID
Store ID
Delivery Partner ID
Order Date
Delivery Time
Delivery Status
Quantity
Unit Price
Revenue
Payment Method
Year
Month
Day
Hour
🔄 Project Workflow
Raw Dataset
      ↓
Data Cleaning
      ↓
Feature Engineering
      ↓
Exploratory Data Analysis (EDA)
      ↓
Power BI Dashboard
      ↓
Business Insights
📊 Dashboard Features
1️⃣ KPI Cards

The dashboard displays key business metrics at the top.

Total Revenue

Displays the total revenue generated from all orders.

Total Orders

Shows the total number of customer orders.

Total Customers

Displays the total unique customers.

Average Order Value

Shows the average revenue generated per order.

2️⃣ Revenue by Month

This clustered column chart displays monthly revenue trends.

Purpose

Identify peak sales months.
Compare monthly business performance.
Understand seasonal demand.
3️⃣ Revenue Comparison (2023 vs 2024)

A line/area chart comparing revenue between 2023 and 2024.

Purpose

Compare yearly performance.
Analyze business growth.
Identify months with improved or decreased revenue.
4️⃣ Revenue by Day

Displays revenue generated on each day of the week.

Purpose

Identify the busiest weekdays.
Understand customer shopping behavior.
5️⃣ Revenue by Hour

Shows hourly sales performance throughout the day.

Purpose

Determine peak ordering hours.
Support staffing and delivery planning.
6️⃣ Revenue by Payment Method

A donut chart displaying revenue contribution by different payment methods.

Payment Methods include:

UPI
Cash
Card
Wallet

Purpose

Identify the most preferred payment option.
Understand customer payment behavior.
7️⃣ Delivery Status Analysis

A pie chart representing delivery performance.

Categories include:

On Time
Slightly Delayed
Significantly Delayed

Purpose

Measure delivery efficiency.
Monitor customer service performance.
8️⃣ Interactive Filters

The dashboard includes multiple slicers:

Delivery Status
Year
Month
Payment Method

These filters allow users to dynamically analyze data based on different business scenarios.

📈 Key Business Insights
Total Revenue generated: ₹4.97 Million
Average Order Value: ₹994.48
Total Orders: 5K
Total Customers: 2K
UPI is one of the most preferred payment methods.
Most deliveries are completed on time.
Revenue varies significantly across different months.
Peak ordering hours are identified using hourly sales analysis.
📷 Dashboard Preview
![Dashboard](Images/Dashboard.png)
📁 Repository Structure
Blinkit-Sales-Analysis-PowerBI
│
├── Dashboard
│   └── Blinkit_Sales_Dashboard.pbix
│
├── Dataset
│   ├── blinkit_final.xlsx
│   ├── blinkit_orders.csv
│   └── blinkit_order_items.csv
│
├── Jupyter Notebook
│   └── Blinkit_Sales_Analysis.ipynb
│
├── Images
│   └── Dashboard.png
│
├── README.md
├── requirements.txt
└── LICENSE
▶️ How to Run the Project
Clone this repository.
Open the Jupyter Notebook to view data cleaning and analysis.
Open the .pbix file using Microsoft Power BI Desktop.
Explore the interactive dashboard using slicers and filters.
📦 Python Libraries
pandas
numpy
matplotlib
openpyxl
jupyter
🚀 Future Improvements
Add Product Category Analysis
Customer Segmentation Dashboard
Store Performance Analysis
Profit Analysis
Forecasting using Machine Learning
Power BI Service Deployment
👩‍💻 Author

Vaishnavi Gavade

Final Year B.Tech (Artificial Intelligence & Data Science)
