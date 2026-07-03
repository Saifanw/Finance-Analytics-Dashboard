# FinSight – Finance Analytics Dashboard

An end-to-end **Business Intelligence (BI)** solution developed using **Power BI** to analyze financial transactions, customer behavior, operational performance, and revenue trends. The project transforms raw financial data into meaningful business insights through **Power Query, Data Modeling, DAX, and Interactive Dashboards**, enabling stakeholders to make informed, data-driven decisions.

---

# Project Overview

FinSight is a comprehensive Finance Analytics Dashboard built to provide a centralized view of an organization's financial performance. The dashboard enables business users to monitor key financial metrics, identify trends, compare year-over-year performance, and analyze customer as well as transaction behavior through an interactive reporting experience.

The project follows the complete Business Intelligence workflow used in real-world organizations:

- Data Collection
- Data Cleaning & Transformation (Power Query)
- Data Modeling
- DAX Measure Development
- Interactive Dashboard Design
- Business Insights Generation

The solution has been developed with a focus on usability, performance, scalability, and business decision-making.

---

# Business Problem

Financial organizations process thousands of transactions every day. Without a centralized reporting solution, management teams often struggle to monitor operational performance, identify customer trends, and evaluate financial growth efficiently.

Key business challenges include:

- Tracking overall transaction growth
- Monitoring monthly financial trends
- Comparing successful and failed transactions
- Identifying high-value customer segments
- Measuring state-wise financial performance
- Understanding customer demographics
- Monitoring fees and tax collections
- Comparing Year-over-Year (YoY) performance
- Supporting faster business decisions through interactive reporting

---

# Solution

To address these challenges, a Finance Analytics Dashboard was developed using Microsoft Power BI.

The dashboard consolidates financial data into a single interactive reporting solution where decision-makers can:

- Monitor KPIs in real time
- Analyze transaction trends across months
- Compare customer segments
- Evaluate state-wise performance
- Monitor operational fees and taxes
- Analyze customer demographics
- Perform Year-over-Year comparison
- Filter reports dynamically using multiple slicers
- Drill into detailed transaction-level information

The dashboard is designed to support business users, analysts, and management teams with actionable insights that improve operational efficiency and strategic decision-making.

---

# Project Objectives

The primary objectives of this project are:

- Build an end-to-end Business Intelligence solution using Power BI.
- Create interactive dashboards for financial reporting.
- Implement efficient data modeling using relationships.
- Develop reusable DAX measures for business KPIs.
- Enable dynamic filtering for better analysis.
- Deliver meaningful insights from transactional data.
- Improve reporting efficiency through automation.
- Provide an intuitive user experience for business stakeholders.

---

# Tech Stack

| Category | Technologies |
|----------|--------------|
| Business Intelligence | Microsoft Power BI |
| Data Transformation | Power Query |
| Data Modeling | Star Schema, Relationships |
| Data Analysis | DAX (Data Analysis Expressions) |
| Data Source | CSV Files |
| Visualization | KPI Cards, Line Chart, Donut Chart, Bar Chart, Matrix |
| Time Intelligence | Calendar Table, Year-over-Year (YoY) Analysis |
| Development Environment | Power BI Desktop |

---

# Dashboard Features

The dashboard provides an interactive analytical experience through the following capabilities:

- Executive KPI Dashboard
- Dynamic Measure Selection
- Interactive Slicers
- Year-over-Year (YoY) Performance Analysis
- Monthly Trend Analysis
- Customer Segment Analysis
- Transaction Status Analysis
- State-wise Financial Analysis
- Transaction Type Analysis
- Gender-based Analysis
- Drill-through Transaction Report
- Cross-filtering Across Visuals
- Responsive Dashboard Layout

---

# Key Performance Indicators (KPIs)

The dashboard tracks the following business metrics:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax
- Previous Year Comparison
- Year-over-Year Growth (%)

These KPIs help stakeholders monitor financial performance and identify business trends efficiently.

---

# Data Model

The project follows a relational data model designed using best practices.

### Fact Table

- Finance Transactions

### Dimension Tables

- Customers
- Calendar Table
- Dynamic Metric Table

The model is designed to improve query performance, simplify DAX calculations, and support scalable reporting.

---

# DAX Measures

Several reusable DAX measures were created to support business reporting and dynamic analysis.

Major measures include:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fee
- Total Tax
- Previous Year Amount
- Previous Year Transactions
- Previous Year Fees
- Previous Year Tax
- Previous Year Average Transaction
- YoY % Amount
- YoY % Transactions
- YoY % Fees
- YoY % Tax
- YoY % Average Transaction
- Selected Dynamic Measure
- Selected Year
- Dashboard Title

The measures were designed using variables, filter context, and time intelligence concepts to ensure reusable and optimized calculations.

---

# Data Preparation

The dataset was prepared using Power Query before visualization.

Data preparation activities included:

- Data Cleaning
- Data Type Validation
- Duplicate Removal
- Relationship Preparation
- Date Formatting
- Calendar Table Creation
- Data Transformation
- Model Optimization

These steps improved overall data quality and reporting accuracy.

---
## Time Intelligence

A dedicated Calendar Table was created to support time-based analysis and improve DAX calculations.

Implemented Time Intelligence features include:

- Calendar Table
- Year Column
- Month Name
- Month Number
- Previous Year (PY) Calculations
- Year-over-Year (YoY) Analysis
- Dynamic Year Selection
- Time-based KPI Comparison

The Calendar Table serves as the central date dimension, enabling efficient filtering and accurate time-based reporting across the dashboard.

## Project Statistics

| Metric | Value |
|---------|-------|
| Dashboard Pages | 2 |
| Fact Tables | 1 |
| Dimension Tables | 3 |
| DAX Measures | 22+ |
| KPIs | 5 |
| Visualizations | 12+ |
| Interactive Filters | 4 |
| Business Requirement Document | Yes |
# Dashboard Preview

## Overview Dashboard

The Overview Dashboard provides a high-level summary of the organization's financial performance through interactive KPIs and analytical visualizations.

Key Highlights:

- Total Amount
- Total Transactions
- Average Transaction Value
- Total Fees
- Total Tax
- Monthly Financial Trend
- Customer Segment Analysis
- State-wise Performance
- Transaction Type Analysis
- Gender-wise Analysis

![Overview Dashboard](Images/Dashboard_Overview.png)

---

## Transaction Details Dashboard

The Transaction Dashboard enables users to explore transaction-level information through dynamic filtering and drill-down analysis.

Features:

- Transaction Details
- Customer Information
- Transaction Type
- Transaction Status
- State
- Gender
- Amount
- Fee
- Tax

![Transaction Dashboard](Images/Dashboard_Transactions.png)

---

## Data Model

The dashboard follows a Star Schema data model designed for performance, scalability, and simplified DAX calculations.

The model consists of:

- Finance Transactions (Fact Table)
- Customers (Dimension)
- Calendar Table (Dimension)
- Dynamic Metric Table

![Data Model](Images/Data_Model.png)

---

# Business Insights

The dashboard enables business users to derive actionable insights such as:

- Identify top-performing customer segments.
- Compare successful, failed, and pending transactions.
- Monitor monthly financial trends.
- Evaluate state-wise financial performance.
- Track operational fees and tax collections.
- Analyze customer demographics.
- Compare current year performance with previous year.
- Support data-driven business decisions through interactive reporting.

---

# Skills Demonstrated

This project demonstrates practical knowledge of:

- Business Intelligence
- Power BI Development
- Data Cleaning
- Power Query
- Data Modeling
- Star Schema Design
- DAX
- Time Intelligence
- KPI Development
- Interactive Dashboard Design
- Business Analytics
- Data Visualization
- Report Optimization
- Drill-through Reporting
- Dynamic Measure Selection

---

# Future Enhancements

Potential improvements for future versions include:

- Live SQL Database Integration
- Incremental Data Refresh
- Row-Level Security (RLS)
- Power BI Service Deployment
- Mobile Dashboard Optimization
- Forecasting and Predictive Analytics
- Bookmark Navigation
- Drill-through Enhancements

---

# Author

**Saif Anwar**

Aspiring Data Analyst | Power BI Developer | SQL | Excel | Python

If you found this project helpful, feel free to explore the repository and connect with me on LinkedIn.

---

# Business Requirements

The dashboard was developed based on documented business requirements that define reporting objectives, KPIs, dashboard layout, and analytical needs.

The complete Business Requirements document is available in the repository:

📄 **Business_Requirements/Business Requirements.docx**

---

# Project Workflow

The project follows a complete Business Intelligence workflow:

```text
Business Requirements
          │
          ▼
Data Collection
          │
          ▼
Data Cleaning (Power Query)
          │
          ▼
Data Transformation
          │
          ▼
Data Modeling
          │
          ▼
Calendar Table Creation
          │
          ▼
DAX Measure Development
          │
          ▼
Dashboard Development
          │
          ▼
Business Insights
          │
          ▼
Decision Making
```

---

# Repository Contents

| Folder | Description |
|---------|-------------|
| Dashboard | Power BI (.pbix) project file |
| Dataset | Source CSV datasets |
| Images | Dashboard screenshots and data model |
| Business_Requirements | Business requirement document |
| README.md | Project documentation |

---

# Learning Outcomes

This project strengthened practical knowledge in:

- Power BI Desktop
- Power Query
- Data Modeling
- Star Schema
- Calendar Table Design
- Time Intelligence
- DAX
- KPI Development
- Interactive Dashboard Design
- Business Analytics
- Financial Reporting
- Report Performance Optimization

---

# Future Scope

Future enhancements planned for this project include:

- SQL Database Integration
- Power BI Service Deployment
- Incremental Refresh
- Row-Level Security (RLS)
- Forecasting
- Predictive Analytics
- Drill-through Enhancements
- Mobile Optimized Dashboard

---

# Contact

**Saif Anwar**

Email - saif.anwar1618@gmail.com

LinkedIn - https://www.linkedin.com/in/saif-anwar-680357376/

Aspiring Data Analyst | Power BI Developer

**Skills**

- Power BI
- SQL
- Excel
- Power Query
- DAX
- Data Modeling
- Python (Learning)

---

## License

This project is licensed under the MIT License.

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub.
