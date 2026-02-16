# Sales Performance & Consumer Behavior Analytics

📌 Project Overview

This repository contains a comprehensive, end-to-end data analysis project investigating consumer purchasing habits. By analyzing a dataset of 3,900 transactions, this project identifies key revenue drivers, customer segments, and product performance metrics.

The goal is to provide actionable business intelligence to optimize marketing spend, increase subscription rates, and improve customer retention.

📂 Repository Structure

File

Description

Shopping_Behavior_Analysis.ipynb

Python notebook for data cleaning, EDA, and feature engineering.

Business_Queries.sql

SQL script (PostgreSQL) for deep-dive revenue and demographic analysis.

Customer_Dashboard.pbix

Interactive Power BI dashboard for visual stakeholder reporting.

Dashboard_Screenshot.png

A high-resolution preview of the finalized dashboard.

Detailed_Analysis_Report.docx

Comprehensive formal report summarizing methodology and findings.

Client_Delivery_Presentation.pptx

Professional slide deck designed for executive-level delivery.

⚙️ Technical Workflow

1. Data Engineering & Cleaning (Python)

The raw data was processed using Python (Pandas) to ensure analytical accuracy:

Imputation: Addressed 37 missing values in the Review Rating column using category-specific medians.

Feature Engineering: Created age_group segments and calculated purchase_frequency_days.

Standardization: Converted all headers to snake_case for seamless SQL integration.

Validation: Performed redundancy checks on promotional data to streamline the feature set.

2. Structured Database Analysis (SQL)

The refined dataset was migrated to PostgreSQL to perform complex relational analysis:

Revenue Mapping: Analyzed spend distribution across genders and age tiers.

Segmentation Logic: Categorized customers into New, Returning, and Loyal tiers based on purchase history.

Logistics Analysis: Compared average spend between Standard and Express shipping methods.

3. Business Intelligence & Visualization (Power BI)

A dynamic dashboard was developed to translate raw data into strategic insights:

KPI Tracking: Real-time monitoring of Average Purchase Amount ($59.76) and Review Ratings (3.75).

Subscription Funnel: Visualized the 73/27 split between non-subscribers and members.

Interactive Filtering: Stakeholders can drill down by region, category, and seasonal trends.

📈 Strategic Recommendations

Conversion Strategy: Target the 73% non-subscriber base with exclusive "Member-Only" perks to drive recurring revenue.

Loyalty Retention: Transition the "Returning" segment into the "Loyal" tier through tiered reward programs.

Inventory Optimization: Prioritize high-rated categories like Footwear (Sandals) and Accessories (Gloves) in promotional campaigns.

Margin Protection: Re-evaluate discount strategies for products with high price sensitivity (e.g., Sneakers).

⚖️ Licensing & Attribution

Original Source

The Power BI dashboard structure and formatting in this project were adapted from a template originally created by [Original Author Name/GitHub Link].

License

This project is licensed under the MIT License.

The Python cleaning scripts, SQL queries, formal reports, and presentation decks are original works.

Consistent with the MIT License, the original copyright notice and permission notice are included in this repository.

Note: This project is for portfolio and educational purposes.
