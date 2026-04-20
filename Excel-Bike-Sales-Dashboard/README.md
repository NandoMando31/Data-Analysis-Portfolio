# Bike Sales Dashboard – Excel Project

## Description
Interactive sales dashboard built in Microsoft Excel to analyze bicycle purchase behavior across different customer segments. This project was completed as part of the [Alex The Analyst Excel Full Course](https://www.youtube.com/watch?v=opJgMj1IUrc&list=PLUaB-1hjhk8Hyd5NiPQ9CND82vNodlFF5&index=7) and covers the full data analyst workflow: data cleaning, pivot tables, and dashboard design.

## Objective
Identify what type of customer is most likely to purchase a bike, based on demographic and behavioral data.

## Dataset
- **Source:** Alex The Analyst – Excel Project Dataset
- **Records:** 1,000 customers
- **Key columns:** Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age, Age Brackets, Purchased Bike

## Data Cleaning Steps
- Removed duplicate rows
- Standardized categorical values (e.g., M/F → Male/Female, M/S → Married/Single)
- Created a new **Age Brackets** column using nested IF formulas (Adolescent / Middle Age / Old)
- Verified data types and formats across all columns

## Analysis – Pivot Tables
Three pivot tables were created to answer key business questions:

| Pivot Table | Analysis |
|---|---|
| Average Income by Gender & Purchase | Do higher-income customers buy more bikes? |
| Count by Age Bracket & Purchase | Which age group buys the most bikes? |
| Count by Commute Distance & Purchase | Does commute distance affect bike purchases? |

## Dashboard
The final dashboard includes 3 charts with slicers for interactive filtering:
- **Bar chart:** Average income by gender (buyers vs. non-buyers)
- **Line chart:** Purchase count by customer age bracket
- **Line chart:** Purchase count by commute distance

**Slicers:** Marital Status | Region | Education

![Bike Sales Dashboard](bike-sales-dashboard-3.pdf)

## Key Findings
- Male customers who purchased a bike had an average income of **$60,124**, higher than non-buyers ($56,208)
- **Middle Age** customers (31–54) represent the largest group of bike buyers
- Customers with a commute of **0-1 miles** were the most likely to purchase a bike
- Europe had the highest number of customers in the dataset

## Files
| File | Description |
|---|---|
| `excel-bike-sales-project-4.xlsx` | Main Excel file: raw data, cleaned data, pivot tables, and dashboard |
| `Excel-Project-Dataset-2.xlsx` | Original dataset |
| `bike-sales-dashboard-3.pdf` | Dashboard screenshot (PDF) |
| `Excel-Project.pdf` | Additional dashboard view |

## Tools Used
- Microsoft Excel (data cleaning, pivot tables, charts, slicers)
- GitHub (version control and portfolio hosting)

## Course Reference
[Alex The Analyst – Excel for Data Analysts](https://www.youtube.com/watch?v=opJgMj1IUrc&list=PLUaB-1hjhk8Hyd5NiPQ9CND82vNodlFF5&index=7)
