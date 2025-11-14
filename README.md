
# Banking Customer Insights and Transaction Analysis (2025)

### Mini Project

## 1. Project Overview

This mini project focuses on analyzing banking customer information and transaction patterns using Excel and Power BI. It covers data cleaning, transformation, modeling, and visualization to identify monthly trends, customer behaviour, transaction types, and branch-level performance.

## 2. Objectives

* Clean and prepare raw banking data for analysis
* Identify customer transaction behaviour and patterns
* Analyze monthly transaction amounts
* Study branch-wise performance
* Examine age-wise and city-wise customer distribution
* Build a structured data model to support visual insights
* Create clear and meaningful charts for reporting

## 3. Dataset Description

Two datasets were used for analysis:

1. **Customer Information** – Contains customer details such as Customer_ID, Name, Age, City.
2. **Transaction Data** – Contains transaction records including Date, Amount, Type, and Customer_ID.

Key fields include:

* Customer_ID
* Transaction_Date
* Amount
* Transaction_Type (Credit/Debit)
* City
* Age

## 4. Excel Data Cleaning

* Removed duplicate records
* Formatted data as structured tables
* Corrected data types (dates, numbers)
* Trimmed extra spaces in text fields
* Removed null and blank records
* Created “Transaction Month” for monthly analysis using date functions

## 5. Power BI Data Preparation

* Loaded cleaned datasets into Power BI
* Removed remaining blank rows using Power Query
* Ensured proper data types for each field
* Applied necessary filters for accurate analysis

## 6. Data Modeling

A relationship was created using **Customer_ID**:

* Customer Information (one)
* Transaction Data (many)

This relationship allows combined analysis of customer profile and transaction activity.

## 7. Visualizations and Insights

### 7.1 Monthly Transaction Amount – Line Chart

Shows monthly trends and helps identify peak/low transaction months.

### 7.2 Transaction Type Distribution – Pie Chart

Shows the split between Credit and Debit transactions.

### 7.3 Branch-wise Transaction Amount – Bar Chart

Displays total transaction amount for each branch (city).

### 7.4 Monthly Transaction Distribution – Doughnut Chart

Highlights the share of each month in overall transaction volume.

### 7.5 Age-wise Customer Count by City – Column Chart

Shows customer distribution across different age groups and cities.

## 8. Key Findings

* Certain months show consistently higher transaction activity
* Credit and Debit proportions indicate customer financial flow
* Specific branches handle higher transaction volumes
* Demographic patterns reveal active age groups in each city

## 9. Conclusion

This project provides a clear understanding of customer behaviour, monthly financial patterns, and branch-level performance. Through systematic data cleaning, modeling, and visualization, the analysis offers meaningful insights for banking operations. The workflow demonstrates how Excel and Power BI can together deliver accurate and visually effective results in customer and transaction analysis.

---

