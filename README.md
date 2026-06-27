# Customer Satisfaction Analysis of Social Development Bank Services

Overview

This project presents an interactive Power BI dashboard that analyzes customer satisfaction with Social Development Bank services.

---

Objectives

- Monitor customer satisfaction across bank services.
- Evaluate service performance using customer ratings.
- Analyze satisfaction trends over time.
- Identify services with the highest and lowest satisfaction levels.
- Support data-driven decision-making through interactive reporting.

---

Dataset

Source:
- Saudi Open Data Platform

The project combines multiple datasets containing:

- Customer information
- Service information
- Service level
- Customer ratings
- Date information

---

Data Preparation

Data preparation was performed using Power Query and included:

- Cleaning missing and inconsistent values.
- Standardizing column names and data types.
- Removing duplicate records.
- Preparing datasets for modeling.

---

Data Modeling

A **Star Schema** was designed to optimize reporting performance and simplify analysis.

The model consists of:

### Fact Table
- Fact_Satisfaction

### Dimension Tables
- Dim_Customer
- Dim_Service
- Dim_ServiceLevel
- Dim_Date

Relationships were established between the fact table and four dimension tables, creating a unified analytical model that enables meaningful insights across customers, services, service levels, and time.

---

## DAX Measures

Custom DAX measures were created, including:

- Average Rating
- Satisfaction Percentage
- Total Beneficiaries
- Total Services

---

## Dashboard Features

The dashboard includes:

- KPI Cards
- Customer Satisfaction Gauge
- Monthly Trend Analysis
- Service Satisfaction Comparison
- Customer Rating Distribution
- Interactive Filters (Service, Service Level, Month)

---

## Key Insights

- **Overall customer satisfaction reached 85.68%, indicating a high level of satisfaction with the bank's services.**
- **Customer satisfaction increased from 83.15% in Jumada Al-Awwal to 89.67% in Rajab, showing a consistent improvement in service quality over the quarter.**
- **Some services achieved a perfect 100% satisfaction rate, demonstrating consistently excellent service quality.**

---

## Tools Used

- Power BI
- Power Query
- DAX
- Star Schema Modeling
- Saudi Open Data Platform

---

## Skills Demonstrated

- Data Cleaning
- Data Modeling
- Star Schema Design
- DAX Calculations
- Power BI Dashboard Development
- Interactive Reporting
- Business Intelligence

---

