Amazon Sales Data Analysis Projec


🧾 Project Overview

This project aims to analyze and extract meaningful insights from Amazon Sales Data to support business decision-making and improve operational efficiency. The dataset includes detailed information about order transactions, fulfillment methods, customer locations, product categories, and sales amounts.

By applying data cleaning, transformation, and visualization techniques, this analysis provides key insights into sales performance, product trends, fulfillment efficiency, and geographical distribution.

🧠 Problem Statement

Analyze and Provide Insights on Amazon Sales Report

The goal of this project is to perform a comprehensive analysis of Amazon’s sales dataset and derive actionable insights that can help optimize sales strategies, improve customer satisfaction, and enhance business performance.

🎯 Key Objectives

Sales Overview: Understand overall sales trends and performance over time.

Product Analysis: Identify top-performing product categories, sizes, and quantities sold.

Fulfillment Analysis: Examine fulfillment methods and their effectiveness.

Customer Segmentation: Segment customers by buying behavior, location, and fulfillment type.

Geographical Insights: Discover sales distribution across different states and cities in India.

Business Insights: Recommend strategies to improve sales, inventory, and customer experience.

🧹 Data Preprocessing & Cleaning

The dataset initially contained 128,976 entries and 21 columns. After cleaning, 128,941 rows were used for analysis.

Key cleaning steps:

Dropped rows with missing shipping details.

Imputed missing fulfilled-by values with "Amazon".

Set quantity and amount to 0 for cancelled orders.

Replaced missing amount values using mean imputation.

Standardized categorical columns (e.g., status, B2B, etc.).

📈 Analysis Summary
1. Financial Insights

Average Quantity: 0.90

Average Transaction Amount: ₹661.41

Amount Range: ₹199.00 – ₹5,584.00

Outlier Rate (IQR Method): 16.6% (≈ 3,747 entries)

2. Fulfillment & Status

Fulfilled by Amazon: 89,691 orders

Top Order Status: Shipped (77,797 occurrences)

Common Shipping Service: Expedited (88,608 occurrences)

B2B Orders: Only 872 compared to 128,069 non-B2B

3. Product Insights

Most Ordered Category: T-shirts (50,280 orders)

Most Popular Size: M (22,366 orders)

Top Category by Sales Amount: T-shirt, followed by Shirt

4. Geographical Insights

All shipments within India

Top Performing State: Maharashtra (22,272 shipments)

📊 Visualizations & Dashboard

Data visualization was a key component of this project. Insights were represented using:

Matplotlib & Seaborn → For EDA, charts, and trend visualization.

Power BI → For interactive dashboards and KPI tracking.

Key visuals included:

Sales trend graphs

Category-wise sales pie charts

Fulfillment method comparisons

State-level sales distribution maps

🛠️ Tools & Technologies Used
Tool / Technology	Purpose
Python	Core programming language
NumPy	Numerical data operations
Pandas	Data cleaning and manipulation
Matplotlib	Static data visualizations
Seaborn	Advanced visual analytics
SQL	Data extraction and querying
Power BI	Dashboard creation and data storytelling
💡 Business Insights & Recommendations

Focus marketing efforts on T-shirt and Shirt categories to maximize sales.

Maintain adequate inventory for popular sizes (M, L).

Enhance Amazon Fulfilled operations, as they dominate total orders.

Leverage Expedited shipping performance to improve customer satisfaction.

Prioritize Maharashtra and other high-demand regions for logistics optimization.

📁 Deliverables

Cleaned dataset and Python notebook with complete analysis

Visualizations and dashboards (Power BI and Python)

Final report summarizing findings and recommendations

🧩 Expected Outcome

This analysis provides data-driven insights to help Amazon (or similar e-commerce platforms):

Improve sales strategies

Optimize inventory management

Enhance fulfillment operations

Understand customer preferences better

👨‍💻 Author

Jatin Pratap Rana
STUDENT NORTHERN INDIA TEXTILE RESEARCH ASSOCIATION(computer science and engineering branch)
