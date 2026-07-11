# Sales Insights Dashboard | Tableau & MySQL

## 📌 Project Overview

This project focuses on analyzing sales performance for **AtliQ Hardware**, a computer hardware and peripherals company operating across multiple markets in India. The company was facing declining sales and needed a better way to identify underperforming areas and uncover growth opportunities.

The objective was to transform raw sales data into meaningful business insights using **MySQL and Tableau** by building an interactive dashboard that helps stakeholders analyze revenue trends, profitability, customer performance, and market opportunities for faster, data-driven decision-making.

## ❓ Business Problem

The company had sales data spread across different regions, customers, products, and transactions, but extracting meaningful insights from raw data was time-consuming and required manual analysis.

The Sales Director needed a centralized dashboard to understand business performance and identify areas for improvement.

Key business questions:

- Which markets and regions are generating the highest revenue?
- Which markets are underperforming and require attention?
- How is revenue trending across different years and months?
- Which customers contribute the most to overall sales?
- Which products are driving maximum revenue?
- Which products and customers have the highest profit contribution?
- How does profit margin vary across different markets?
- Which markets are generating low or negative profit margins?
- How is revenue performance changing compared to profit performance over time?
- Which customer segments contribute more to sales — Brick & Mortar or E-Commerce?
- Where should the business focus its sales and growth strategies?
- How can stakeholders reduce manual reporting efforts and make faster data-driven decisions?

## 📂 Dataset & Data Source

The dataset consists of multiple tables:

1. Transactions Table
148K+ sales transactions
Sales quantity
Sales amount
Profit margin
Profit
Cost price
Order date

2. Customers
Customer details
Customer type (Brick & Mortar / E-Commerce)

3. Products
Product details
Product category

4. Markets
Market information
Regional zones

5. Date Table
Date hierarchy
Year and month analysis

The sales data was extracted from MySQL and connected with Tableau. Data preparation included standardizing fields, handling null values and data inconsistencies, correcting invalid transactions, creating table relationships, and developing calculated fields for sales and profitability analysis.

## 📊 Dashboard Development

An interactive Tableau dashboard was developed with two key analytical views — **Revenue Analysis** and **Profit Analysis** — to provide stakeholders with a comprehensive understanding of sales performance.

### Revenue Analysis Dashboard

Provides insights into:
- Overall revenue and sales quantity performance
- Revenue trends across different years and months
- Market and regional sales contribution
- Top-performing customers and products
- Sales quantity comparison across markets

### Profit Analysis Dashboard

Focuses on profitability analysis through:
- Revenue vs profit trends over time
- Profit margin performance across markets
- Customer-level revenue, profit, and margin analysis
- Contribution of different customer segments (Brick & Mortar vs E-Commerce)

The dashboard enables users to interact with filters and explore sales performance from multiple business perspectives for better decision-making.

## 🔍 Key Insights

The Tableau dashboard analysis helped answer key business questions around revenue performance, profitability, customer behavior, and market opportunities.

### 📈 Revenue & Market Performance
- **Delhi NCR** was identified as the highest revenue-generating market, making it the largest contributor to overall sales.
- The **North region** showed the strongest revenue performance compared to Central and South regions.
- Revenue trends across years and months highlighted changes in sales performance and seasonal patterns.
- Markets with lower revenue contribution were identified for further analysis and improvement.

### 👥 Customer & Product Analysis
- Top-performing customers were identified based on revenue contribution, highlighting key accounts driving sales.
- High-revenue products were analyzed to understand major sales drivers and support product planning.
- Customer-level analysis revealed which customers contributed the highest revenue and profit.
- **Brick & Mortar customers** contributed the majority of sales compared to E-Commerce customers.

### 💰 Profitability Analysis
- Profit and revenue trends were compared over time to understand business performance changes.
- Profit margin analysis across markets identified high-performing and low-performing regions.
- Markets with low or negative profit margins were highlighted for pricing and cost optimization opportunities.

### 🔗 Business Recommendations
- Focus sales strategies on high-performing markets, customers, and products to maximize growth.
- Investigate low-profit markets to improve margins through pricing and operational improvements.
- Use automated Tableau reporting to reduce manual data gathering and enable faster, data-driven decisions.

## 👨‍💼 Business Impact & Stakeholder Benefits

The Tableau dashboard provides a centralized view of sales and profitability performance, helping stakeholders:

- Quickly identify revenue trends, market performance, and areas requiring improvement.
- Understand customer and product behavior to discover growth opportunities.
- Make faster, data-driven strategic decisions using interactive sales insights.
- Reduce manual reporting efforts by replacing large Excel-based analysis with an automated dashboard.
- Save analyst time spent on data gathering and focus more on value-added analysis.
- Monitor overall business performance and support future sales planning.
