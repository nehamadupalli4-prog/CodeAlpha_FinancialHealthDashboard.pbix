Financial Health Dashboard – Power BI
Overview

This project was developed as part of the CodeAlpha Power BI Internship. The dashboard provides a comprehensive analysis of an organization's financial performance through interactive visualizations and key financial metrics. It helps users understand revenue, profitability, cash flow trends, and financial performance across different countries and products.

Objective

To create an interactive Financial Health Dashboard that enables:

Financial performance monitoring
Profitability analysis
Cash flow analysis
Financial forecasting
Data-driven decision making
Dataset

Dataset Used: Microsoft Financial Sample Dataset

The dataset contains:

Sales
Profit
COGS (Cost of Goods Sold)
Product Information
Country Information
Segment Details
Date-wise Financial Data
Dashboard Features
Key Performance Indicators (KPIs)
Total Revenue
Total Profit
Total Units Sold
Profit Margin (%)
Net Cash Flow
Financial Analysis
Income Statement Analysis
Product-wise Revenue, Profit, and COGS Comparison
Country-wise Financial Performance
Cash Flow Analysis
Trend Analysis
Profit Trend Over Time
Financial Performance Tracking
Historical Profit Analysis
Forecasting
Future Profit Forecasting
Budget Planning Support
Financial Trend Prediction
Interactive Filters
Product Filter
Segment Filter
Country Filter
Tools & Technologies
Power BI Desktop
DAX (Data Analysis Expressions)
Data Modeling
Data Visualization
Forecasting Analytics
DAX Measures Used
Profit Margin %
Profit Margin % =
DIVIDE(
SUM(financials[Profit]),
SUM(financials[Sales]),
0
) * 100
Cash Flow
Cash Flow =
SUM(financials[Sales]) -
SUM(financials[COGS])
Dashboard Insights
Identified top-performing products based on revenue and profit.
Analyzed profitability trends across different periods.
Compared financial performance across countries.
Evaluated cash flow patterns for financial planning.
Generated forecasts to support budgeting and strategic decisions.
Project Deliverables
Power BI Dashboard (.pbix)
Interactive Financial Reports
Financial Forecasting Visualizations
KPI Monitoring Dashboard
Learning Outcomes

Through this project, I gained hands-on experience in:

Power BI Dashboard Development
Data Visualization Best Practices
DAX Measure Creation
Financial Data Analysis
Forecasting and Trend Analysis
Interactive Report Design
Author

Neha Madupalli

Internship: CodeAlpha Power BI Internship
