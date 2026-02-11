📊 Finance Summary Dashboard (Excel MIS Reporting)
🧾 Overview

This project is an interactive Management Information System (MIS) dashboard created in Microsoft Excel to monitor an organization’s financial performance.
The dashboard provides a consolidated view of revenue, expenses, and profitability, helping managers track operational efficiency and make data-driven decisions.

The objective of the project was to replicate a real corporate monthly reporting system where leadership reviews financial KPIs and department performance.

🎯 Business Problem

Organizations often maintain financial data across multiple sheets and files, making reporting slow and error-prone.
Manual reporting requires hours of work every month and increases the risk of incorrect calculations.

This dashboard solves that problem by:

Centralizing financial data

Automating KPI calculations

Providing dynamic filtering and drill-down analysis

🛠 Tools & Skills Used

Microsoft Excel (Advanced)

Power Pivot Data Model

Power Query (Data Cleaning & Transformation)

Pivot Tables & Pivot Charts

DAX Calculations

Data Validation & Data Structuring

📈 Key Dashboard Metrics

The dashboard tracks the following KPIs:

Total Revenue

Total Expense

Profit & Loss

Maximum Revenue

Maximum Expense

Monthly Profit Trend

Department-wise Financial Performance

Category-wise Revenue & Expense

🧠 Data Modeling

A relational data model was created using Excel Power Pivot.

Fact Table

Financial_Transactions

Date

Department

Category

Payment Method

Revenue Amount

Expense Amount

Dimension Tables

Date Table (Year, Month, Quarter)

Department

Category

Payment Method

Relationships were created between tables to allow accurate aggregations and slicer filtering.

🔄 Data Preparation (ETL)

Data was prepared using Power Query:

Removed duplicates and blank records

Standardized department and category names

Converted data types

Created Month and Quarter columns

Structured data for reporting model
💼 Business Impact

The dashboard helps stakeholders:

Monitor company financial health

Identify high expense areas

Compare department performance

Track monthly profit trends

Reduce manual reporting effort
