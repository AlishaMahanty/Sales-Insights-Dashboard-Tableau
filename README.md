# Sales Insights Dashboard | Tableau & MySQL

## 📌 Project Overview

This project focuses on analyzing sales performance for AtliQ Hardware, a computer hardware and peripherals company operating across multiple markets in India. The company was facing declining sales and needed better visibility into sales performance, profitability, and growth opportunities.

The objective was to transform raw sales data into meaningful business insights using MySQL and Tableau by building an interactive dashboard that helps stakeholders analyze revenue trends, customer behavior, product performance, and market opportunities for faster, data-driven decision-making.

## ❓ Business Problem

The company had sales data spread across multiple regions, customers, products, and transactions, but extracting meaningful insights from raw data was time-consuming and required manual Excel-based analysis.

The Sales Director needed a centralized dashboard to understand business performance, identify underperforming areas, and make informed sales decisions.

Key business questions:

- Which markets and regions are generating the highest revenue?
- Which markets are underperforming and require attention?
- How is revenue and profit performance changing over time?
- Which customers and products are driving maximum revenue?
- Which products and customers have the highest profit contribution?
- How does profit margin vary across different markets?
- Which markets are generating low or negative profit margins?
- How is revenue performance changing compared to profit performance over time?
- Which customer segments generate more revenue?
- Where should the business focus its sales and growth strategies?

## 📂 Dataset & Data Source

The dataset consists of multiple tables:

| Table Name | Description | Key Fields |
|------------|-------------|------------|
| Transactions | 148K+ sales transaction records used for revenue and profit analysis | Sales Quantity, Sales Amount, Profit Margin, Profit, Cost Price, Order Date, Product Code, Customer Code, Market Code |
| Customers | customer information and customer segment details | Customer Code, Customer Name, Customer Type |
| Products | product details and product category information | Product Code, Product Type |
| Markets | market and regional information for geographical analysis | Market Code, Market Name, Zone |
| Date | time-based analysis and trend identification | Date, Year, Month, Year-Month |

The sales data was extracted from MySQL and connected with Tableau. Data preparation included standardizing fields, handling null values and data inconsistencies, correcting invalid transactions, creating table relationships, and developing calculated fields for sales and profitability analysis.

## 📊 Dashboard Development

An interactive Tableau dashboard was developed with two analytical views — Revenue Analysis and Profit Analysis — providing stakeholders with a complete understanding of sales and profitability performance.

### Revenue Analysis Dashboard

![](https://github.com/AlishaMahanty/Sales-Insights-Dashboard-Tableau/blob/main/Revenue_Analysis.png)

Provides insights into:
- Overall revenue and sales quantity performance
- Revenue trends across different years and months
- Market and regional sales contribution
- Top-performing customers and products
- Sales quantity comparison across markets

### Profit Analysis Dashboard

![](https://github.com/AlishaMahanty/Sales-Insights-Dashboard-Tableau/blob/main/Profit_Analysis.png)

Focuses on profitability analysis through:
- Revenue vs profit trends over time
- Profit margin performance across markets
- Customer-level revenue, profit, and margin analysis
- Contribution of different customer segments (Brick & Mortar vs E-Commerce)

The dashboard enables users to interact with filters and explore sales performance from multiple business perspectives for better decision-making.

## 🔍 Key Insights

The dashboard analysis revealed important insights around revenue performance, profitability, customer behavior, product performance, and market opportunities.

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
