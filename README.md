
# Banking Customer Insights and Transaction Analysis (2025)

### Mini Project Documentation

## 1. Project Overview

This project focuses on understanding customer behaviour and transaction trends in a banking environment. Using Excel and Power BI, two datasets were cleaned, transformed, modelled, and visualized to extract meaningful insights. The study covers monthly transaction patterns, customer demographics, branch performance, and transaction type distribution.
The goal of the project is to prepare the data for reporting, explore hidden patterns, and support decision making in customer and branch-level operations.

---

## 2. Objectives

The main objectives of this mini project include:

* Cleaning and preparing raw customer and transaction data for analysis
* Understanding monthly financial movement through transaction amounts
* Comparing transaction performance across different branches
* Identifying active customer groups based on age and city
* Separating credit and debit patterns to study financial flow
* Building a meaningful data model using Customer_ID
* Creating clear visualizations to present the findings
* Summarizing key outcomes that support business understanding

---

## 3. Dataset Description

Two datasets were used from the Banking_Mini_Project spreadsheet:

### 3.1 Customer Information

Contains demographic details of each customer.
Important fields:

* Customer_ID
* Name
* Age
* City
* Contact Information

### 3.2 Transaction Data

Contains detailed records of transactions performed by customers.
Important fields:

* Transaction_Date
* Amount
* Transaction_Type (Credit/Debit)
* Customer_ID (foreign key)
* Mode of Transaction
* Branch/City

These two sheets together provide both **who** the customer is and **how** they transact.

---

## 4. Excel Data Cleaning

Data cleaning was performed separately on each sheet to ensure high-quality inputs for Power BI.

### 4.1 Removing Duplicate Records

Duplicate rows were identified and removed using Excel’s “Remove Duplicates” feature to maintain unique customer and transaction entries.

### 4.2 Formatting Data as Tables

Both sheets were converted into Excel Tables.
This enabled structured referencing, easier sorting, and cleaner filtering.

### 4.3 Correcting Data Types

* Transaction Date columns were converted to Date format.
* Amount fields were set to Number / Currency.
* Customer_ID and Age fields were checked for consistency.
  Correct data types ensure accurate calculations and grouping.

### 4.4 Trimming Extra Spaces

TRIM function was applied to text fields (Name, City, Branch) to remove unnecessary spaces and standardize text values.

### 4.5 Handling Null and Blank Values

Rows with missing Customer_ID or Amount were removed because they affect analysis and modeling accuracy.

### 4.6 Creating Additional Columns

A “Transaction Month” column was created using:
`=TEXT(TransactionDate, "mmmm")`
This field helps in month-wise visualization and analysis.

---

## 5. Power BI Data Preparation

After loading the cleaned Excel tables into Power BI:

### 5.1 Removing Blank Rows

Power Query Editor was used to filter and remove rows containing blank or null values in key fields.

### 5.2 Verifying Data Types

Date, text, and numerical fields were checked to ensure consistency before modeling and visualization.

### 5.3 Preparing Data for Relationship Building

Customer_ID was reviewed in both tables for uniqueness and accuracy, which is essential for a reliable data model.

---

## 6. Data Modeling

### 6.1 Relationship Between Tables

A relationship was created in Power BI using:
**Customer Information (primary key) → Customer_ID → Transaction Data (foreign key)**

### 6.2 Relationship Type

One-to-Many

* One customer can have multiple transactions
* Ensures accurate cross-filtering between tables

### 6.3 Purpose of the Data Model

* Combine customer profile and activity
* Allow demographic-based transaction analysis
* Enable city-wise and age-wise comparisons
* Support consistent aggregation across the dashboard

---

## 7. Visualizations and Insights

### 7.1 Monthly Transaction Amount – Line Chart

* Shows transaction totals across each month
* Identifies high and low activity periods
* Helps with planning and financial forecasting

### 7.2 Transaction Type Distribution – Pie Chart

* Separates Credit and Debit values
* Helps understand customer financial behaviour
* Useful for studying cash inflow vs outflow

### 7.3 Branch-wise Transaction Amount – Bar Chart

* Displays which branches (cities) handle the highest transaction amounts
* Highlights strong and weak performing regions
* Supports branch-level operational planning

### 7.4 Monthly Transaction Amount Distribution – Doughnut Chart

* Breaks down the proportion of each month’s transaction contribution
* Clear visual representation of monthly importance

### 7.5 Age-wise Customer Count by City – Column Chart

* Shows how different age groups are spread across cities
* Useful for customer targeting, age-based marketing, and service distribution

---

## 8. Key Findings

* Certain months consistently show higher transaction activity
* Credit vs Debit split reveals customer money movement patterns
* Some branches process significantly more transactions than others
* Middle-aged customer groups tend to be more active
* Cities show varied demographic and transaction behaviour
* Transaction amounts are concentrated in specific months and branches

---

## 9. Conclusion

This mini project provides a complete end-to-end analysis of customer and transaction data using Excel and Power BI. Through systematic cleaning, modeling, and visual exploration, the project offers clear insights into customer demographics, monthly transaction trends, and branch performance.
The results support better understanding of customer activity and branch-wise financial movement, forming a strong base for further banking analytics, targeted interventions, planning, and reporting.

---


Just tell me!
