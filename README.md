# Assignment-1-Power-BI
# 📊 E-Commerce Sales Analysis – Power BI

## 📌 Project Overview

This project is a Power BI data transformation and data modeling assignment based on an **E-Commerce Sales dataset**.

The project focuses on cleaning, transforming, combining, and modeling sales data using **Power BI and Power Query**.

## 🎯 Objectives

- Import and transform multiple datasets
- Clean and prepare the data
- Create calculated and conditional columns
- Merge related tables
- Handle missing values and duplicates
- Perform grouping and aggregation
- Create relationships between tables
- Prepare the data for analysis in Power BI

## 📂 Datasets Used

The project uses three datasets:

1. **List of Orders.csv**
2. **Order Details.csv**
3. **Sales target.csv**

## 🛠️ Tools & Technologies

- Microsoft Power BI
- Power Query
- Data Modeling
- CSV datasets

## 🔄 Data Transformation

The following transformations were performed:

- Kept the first **500 rows** from List of Orders
- Changed **Order Date** to Date format
- Changed **Amount** and **Target** to Fixed Decimal Number
- Converted Customer Name to **Proper Case**
- Merged **City and State** into a Location column
- Created **Profit Margin**
- Created **Profit Status**:
  - Profit
  - Loss
  - Break-Even
- Merged List of Orders and Order Details using **Order ID**
- Checked for missing values and duplicates
- Sorted Order Date in descending order
- Applied state/location filtering

## 📈 Data Aggregation

The following aggregations were performed:

- Count of each **Order ID**
- Average **Profit by Category**
- Total **Amount by Sub-Category**
- Total **Target by Month**

## 🔗 Data Modeling

Relationships were created between the tables using:

- **List of Orders → Order Details**
  - Relationship based on `Order ID`

- **Order Details → Sales Target**
  - Relationship based on `Category`
  - Relationship kept active

## 📊 Project Outcome

The transformed and modeled data can be used to analyze:

- Sales performance
- Profit and loss
- Product categories
- Sub-categories
- Monthly sales targets
- Order-level information

## 📁 Project Files

```text
📦 E-Commerce-Sales-PowerBI
 ├── 📄 List of Orders.csv
 ├── 📄 Order Details.csv
 ├── 📄 Sales target.csv
 ├── 📊 E-Commerce Sales Analysis.pbix
 └── 📄 README.md
