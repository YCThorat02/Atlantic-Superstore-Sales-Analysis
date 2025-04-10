# Atlantic-Superstore-Sales-Analysis

### Tableau Public Account Link 
https://public.tableau.com/app/profile/yash.thorat3350/viz/Atlantic_Superstore_Analysis/Story1

# Overview
This Tableau project provides a detailed analysis of sales, profit, and returns for the Atlantic Superstore, focusing on data from 2017 and 2018. It integrates multiple data sources, applies necessary transformations, and visualizes key business metrics. The project helps identify trends, track sales performance against goals, analyze product categories, and evaluate the impact of returns on profitability. Additionally, a specific focus is placed on 2018 sales performance through a filtered dashboard. The insights derived from this analysis can support better decision-making and business strategy optimization.

![Atlantic Superstore](https://github.com/user-attachments/assets/bd14f3ac-3fe9-475a-ac52-d9231dd243f2)

# Tools Used 
![tableau](https://github.com/user-attachments/assets/1444a496-be85-443b-9f2c-a8be3833b25c)

# Data Preparation

## 1. Data Source Filtering:
Applied a filter to include only data from the years 2017 and 2018.

## 2. Union of Order add-on Data:
Combined the Orders and Orders Add-On sheets using a union to ensure all order records were included.

## 3. Joining Returns Data:
Used a left join to integrate the Returns sheet, ensuring order-level return data was available for analysis.

## 4. Data Cleaning & Transformation:
Reorganized messy data by converting rows into proper column formats.

## 5. Created new calculated columns:
### Country ABB 
Standardized country abbreviations
### Ship Mode Group 
Categorized shipping methods into groups
### Sub-Category Group 
Extracted sub-category groups for better analysis

# Key Features of the Executive Retail Sales Dashboard:
Sales vs Goal Analysis – Compares actual sales with predefined goals  for different regions in 2018:

Regional Performance Insights – Highlights which regions exceeded targets (West & Central) and which underperformed (East & South):

Sales & Profit by City (Map) – Displays sales distribution geographically, helping identify high and low-performing cities:

Category & Sub-Category Breakdown – Analyzes sales contribution and profitability across different product categories:

Monthly Sales & Profit Trends – Shows seasonal trends, identifying peak and slow months:

Key Metrics (KPIs) – Provides a high-level overview of total sales, profit, and order volume:

Interactive Filters – Allows users to explore data dynamically by region, category, and time period:

# Analysis by Stories
![Dashboard 1(ny)](https://github.com/user-attachments/assets/cc0cbede-ae11-4681-bbf2-675b7158a7f7)

### This dashboard shows Atlantic Superstore's 2018 NYC sales with strong overall YTD figures, but the East region is significantly underperforming its sales goal.  A potential data duplication error needs clarification.  The map visualization lacks detail, and further investigation into the East's shortfall is crucial.

![Dashboard 1 (2)](https://github.com/user-attachments/assets/10bb4306-6733-4448-9c94-19eb991d509c)

### This Atlantic Superstore dashboard reveals strong overall 2018 sales, but the West region is significantly underperforming its sales goal, requiring immediate attention.  The city map shows sales distribution, and the monthly trend chart indicates a peak in September.

![Dashboard 1 (3)](https://github.com/user-attachments/assets/5ee6767e-48b6-4c00-8f06-90057e48dff5)

### This Atlantic Superstore dashboard shows a moderate 2018 sales performance, with $545.01K in YTD sales and $88.25K profit.  The West region is significantly outperforming its sales goal, while Central is underperforming.  The monthly sales trend indicates a peak in March. 































 



