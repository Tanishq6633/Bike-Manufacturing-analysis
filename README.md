Bike Manufacturing and Inventory Analysis
Overview

This project delivers a production and inventory performance analysis for the Microsoft AdventureWorks bicycle manufacturing database. The objective was to design a scalable data model, apply analytical techniques, and build an interactive reporting solution that enables decision-makers to optimize production efficiency, reduce costs, and manage inventory more effectively.

Business Problem

Manufacturing companies often face challenges such as:

Rising production costs due to inefficient resource allocation

High waste and scrap percentages impacting margins

Ineffective inventory turnover leading to capital lock-up

This project addresses these challenges by transforming raw ERP data into actionable insights.

Technical Approach

Data Extraction and Preparation

Queried AdventureWorks ERP dataset using SQL Server

Modeled data into a star schema for efficient querying

Pre-processed data with Python for cleaning and transformation

Data Modeling

Fact tables: Production Work Orders, Inventory Transactions, Sales Orders

Dimension tables: Product, Location, Category, Scrap Reason

Established relationships to support drill-down analytics

Visualization and Reporting

Developed Power BI dashboards with custom KPIs and DAX measures

Designed fiscal year calendar (Oct–Sep) for time-based analysis

Implemented interactive navigation for Production and Inventory views

Key Insights

Identified top 20% of product components driving ~80% of production costs (Pareto principle)

Highlighted fiscal year trends in waste cost, enabling corrective actions in high-loss areas

Revealed assembly lines with disproportionate inventory value holdings, improving allocation decisions

Demonstrated declining inventory turnover in specific categories, indicating potential overproduction

Business Impact

Cost transparency across production lines → informed decisions on component sourcing

Waste reduction opportunities identified, with potential to cut scrap costs by up to 15%

Optimized inventory allocation, reducing working capital lock-up

Enabled leadership to monitor KPIs in real time via a centralized dashboard

Tech Stack

Python – data cleaning and preprocessing

SQL Server – data extraction and schema modeling

Power BI – interactive dashboards, KPIs, and advanced DAX calculations

Outcome

The solution demonstrates how enterprise-scale ERP data can be transformed into an analytics product. By combining SQL, Python, and Power BI in a star schema model, the project provides a foundation for scalable manufacturing analytics and equips stakeholders with actionable intelligence to improve operational efficiency.
