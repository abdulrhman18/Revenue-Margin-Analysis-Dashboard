# Revenue-Margin-Analysis-Dashboard
Project Overview
This Power BI project provides a comprehensive analysis of financial performance, focusing on revenue trends, profitability margins, and sales team efficiency. The dashboard is designed to transform raw transactional data into actionable business insights, allowing stakeholders to monitor KPIs in real-time and identify growth opportunities across different sales channels and product categories.

Key Features
Dynamic Visuals: Interactive charts including Revenue vs. Last Month (LM) trends, Net Profit Stepped Area charts, and Donut charts for categorical distribution.

Advanced DAX: Implementation of Time Intelligence functions (YoY, MoM growth) and complex measures for Net Profit and Gross Margin.

User Experience (UX): Integrated Dark/Light Mode toggle and a custom Filter Pane for deep-dive analysis by Month, Supplier, and Supervisor.

Tooltips: Custom report page tooltips providing granular breakdowns (e.g., Team revenue details) without cluttering the main view.

Data Modeling: A robust Star Schema implementation for optimized performance and scalability.

Dashboard Preview
1. Main Dashboard (Dark Mode)
The primary interface for high-level executive reporting.

2. Main Dashboard (Light Mode)
Alternative viewing mode for different user preferences.

3. Advanced Filtering & Navigation
Custom sidebar for multi-dimensional data slicing.

4. Custom Report Tooltips
Context-aware tooltips for deeper insights into specific data points.

Data Model & Architecture
The project follows best practices in data modeling to ensure accuracy and speed.

Schema: Star Schema.

Fact Tables: Revenue and Expenses.

Dimension Tables: Product, Sales Person, Calendar, and Account Hierarchy.

Tech Stack
Power BI Desktop: Report authoring and dashboard design.

DAX (Data Analysis Expressions): For complex calculations and business logic.

Power Query (M): For ETL (Extract, Transform, Load) processes and data cleaning.

Power BI Theme JSON: To handle the Dark/Light mode toggle functionality.

Key Insights Found
Seasonal Trends: Significant revenue peaks identified in October and November.

Performance Leaders: "Shahid Duran" emerged as the top-performing salesperson, contributing $2.3M in revenue.

Product Performance: The "Food" category dominates the revenue share at 90.88% compared to "Drinks."

Channel Efficiency: The "Wholesales" team leads in revenue contribution, followed by "Retail" and "Online."

How to Use
Download the .pbix file from this repository.

Open it using Power BI Desktop.

Use the toggle switch in the top right to switch between Dark and Light modes.

Click the filter icon to expand the slicer panel and filter by specific categories or timeframes.

Author: Abdulrahman Ahmed

Data Analyst | Power BI Specialist
