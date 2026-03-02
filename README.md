# Retail-Customer-Intelligence-RFM-Analytics-Platform

This project delivers an end-to-end Retail Analytics & Customer Intelligence solution built using Python and Power BI.
The objective is to transform raw transactional data into actionable business insights through:

- Advanced data cleaning & transformation (Python)
- Parquet-based curated data layer
- Star schema semantic modeling
- RFM customer segmentation
- Interactive drillthrough dashboards
- Context-aware tooltips for enhanced UX
  
This solution simulates a real-world freelance consulting engagement for a retail or e-commerce business.

🎯 Business Objectives
The dashboard answers critical business questions:
-Who are our most valuable customers?
-Where is revenue concentrated?
-Which customers are at risk of churn?
-Which products drive repeat purchases?
-How healthy is our customer base?

🏗️ Solution Architecture
Raw Excel Data
⬇
Python Data Cleaning & Feature Engineering
⬇
Parquet Curated Layer (Analytics Ready)
⬇
Power BI Star Schema Model
⬇
Executive & Customer Intelligence Dashboards

🧱 Data Engineering Layer (Python)

Implemented:
-Data cleaning and validation
-Type casting and schema standardization
-Revenue calculation
-Date dimension creation
-Customer feature engineering
-RFM scoring and segmentation

RFM Logic
-Recency → Days since last purchase
-Frequency → Number of distinct orders
-Monetary → Total revenue generated

Segments created:
-Champion
-Loyal
-At Risk
-Others

📈 Dashboard Pages
1️⃣ Executive Overview

-Total Revenue
-Total Orders
-Total Customers
-Revenue Trends
-Country Performance
-Top Products

2️⃣ Customer Intelligence (RFM)

-Customer Distribution by Segment
-Revenue by Segment
-Repeat Purchase Rate
-Champion Revenue %
-At Risk Customer Count

3️⃣ Product Insights

-Product Revenue Trends
-Repeat Purchase Rate per Product
-Top Customers by SKU

🔍 Advanced UX Features
🔹 Customer 360° Drillthrough

Allows deep analysis of individual customer behavior:
-Revenue trend
-Order frequency
-Purchase history
-Recency & Monetary metrics

🔹 Product Drillthrough

Detailed SKU performance analysis:
-Revenue trend
-Top buying countries
-Top customers

🔹 Interactive Tooltips

Context-aware mini insights without navigating away.

🧠 Advanced Analytics Implemented
-RFM Customer Segmentation
-Cumulative Revenue %
-Customer Lifetime Value (CLV)
-Repeat Purchase Rate
-Revenue Concentration Risk Analysis

📊 Sample Business Insights

-Top 20% of customers contribute ~65% of revenue.
-Champions represent a small portion of customers but drive significant revenue.
-Identified churn-risk customers contributing measurable revenue share.

🛠️ Tech Stack
-Python (Pandas, PyArrow)
-Parquet Storage
-Power BI Desktop
-DAX (Advanced calculations using CALCULATE, FILTER, RANKX, etc.)
-Star Schema Modeling

Star Schema Modeling
