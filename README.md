# Madhav-Ecommerce-Sales-Dashboard
🛒 Madhav E-commerce Sales Performance Dashboard
Project Overview
This Power BI dashboard provides a detailed, interactive analysis of Madhav E-commerce sales and profitability. The primary focus is on integrating transactional data with order information to deliver a 360-degree view of sales performance, profitability across product categories, and the efficiency of various payment methods.

The dashboard's goal is to enable stakeholders to quickly diagnose issues like negative profitability, optimize product inventory, and assess the financial health of different sales channels (geography and payment mode).

Tech Stack
Component

Technology/Language

Data Visualization      -Power BI

Data Modeling / ETL     -Power Query (Merging/Cleaning)

Calculations            -DAX (Data Analysis Expressions)

Data Source             -Multiple CSV Files (Orders & Details)

Data Source
This analysis uses two separate datasets that required modeling (a one-to-many relationship based on Order ID) within Power Query/Power BI:

Orders.csv: Contains geographical and customer details (Order ID, State, City, CustomerName).

Details.csv: Contains transactional and financial data (Order ID, Amount, Profit, Quantity, Category, Sub-Category, PaymentMode).

Key combined fields used for analysis include: Amount, Profit, Quantity, Category, Sub-Category, PaymentMode, State, and City.

Features & Highlights (Interview Focus)
This section frames the analysis for an interview, highlighting your problem-solving process and business insights.

1. Business Problem Solved
The e-commerce business had fragmented data, making it impossible to see the end-to-end performance of a single order (i.e., linking the product details and profit to the customer's location). Furthermore, they lacked clarity on which product lines or payment modes were consistently leading to losses.

2. Dashboard Goal
The core goal was to merge the two datasets and create a dynamic, single-page dashboard that focuses heavily on Profitability Ratio and Payment Mode Analysis. It needed to provide immediate answers on:

Top-selling vs. Top-profitable products.

The split between Digital Payments (UPI/Credit Card) and Cash on Delivery (COD/EMI).

3. Key Visuals Used
The following visuals were utilized to maximize data clarity and actionability:

Profit vs. Loss Breakdown (Donut/Pie Chart): Instantly highlights the ratio of profitable transactions versus loss-making transactions, drawing immediate attention to core issues.

Amount and Profit by Category (Stacked Bar Chart): Compares total revenue against profit for each product category, identifying where high sales volume might mask low profitability.

Payment Mode Distribution (Bar Chart): Shows the total sales amount contributed by each payment type (COD, UPI, EMI, Credit Card) to inform payment gateway strategy.

Sales Trend over Time (Line Chart): Analyzes sales growth or decline over the reporting period.

Geographical Sales Map (Sales by State): Pinpoints top-performing regions for targeted marketing and logistics planning.

4. Business Impact & Actionable Insights
The analysis facilitates the following strategic actions:

Loss Mitigation: The Profit vs. Loss breakdown identified specific Sub-Categories (e.g., certain types of Furniture or Clothing) that consistently show negative profit. These items require an immediate price review or supplier cost negotiation.

Payment Strategy: The analysis of payment modes provides clear data on the popularity of Cash on Delivery (COD). Management can use this to assess associated risks (higher returns, logistics costs) and potentially incentivize digital payments.

Inventory Prioritization: Electronics were identified as the highest-profit category, suggesting marketing and inventory efforts should be prioritized here rather than solely focusing on high-volume, low-profit categories.
