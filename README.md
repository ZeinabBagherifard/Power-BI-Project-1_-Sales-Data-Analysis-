# Power BI Sales Data Analysis
Power BI Project 1: Sales Data Analysis (Covers Data Modeling Concepts)

## Overview
This project analyzes sales data in Power BI and focuses on data modeling concepts, DAX calculations, and interactive dashboard design.

## Tools Used
- Power BI
- Excel

## Dataset
The dataset used in this project is included in the repository as `Store+Data.xlsx`.

## Preparation
After loading the dataset into Power BI, the preparation phase began by `Data Transformation`. This included checking data types, potential primary keys, null values, headers, and table names.

For example, since `Customer ID` is a potential primary key, its data type was changed from **Whole Number** to **Text**. In addition, in the `Dim Promotion` table, the `Price Reduction Type` column was converted into numerical values by creating a new column.

We can also fill nullvalues in Sheet3 table *which is renamed to *Fact table with join or calculations. Like (Net Sales = Total Sales - Discount Value)
