# Week 3 – Retail Store KPI Dashboard using Power BI

## Project Description
This project focuses on analyzing retail sales performance using Microsoft Power BI. It uses DAX functions, KPI cards, slicers, charts, and conditional formatting to understand sales, profit, and business performance.

## Tools Used
- Microsoft Power BI Desktop
- Microsoft Excel
- DAX (Data Analysis Expressions)

## Dataset
**Global Superstore 2016 Dataset**

The dataset contains three tables:
- Orders
- People
- Returns

## Tasks Completed

### 1. Data Import and Preparation
- Imported the Global Superstore dataset into Power BI.
- Loaded Orders, People, and Returns tables.
- Checked and prepared table columns and data types.

### 2. Data Modeling
Created relationships between:
- Orders and People using Region.
- Orders and Returns using Order ID.

### 3. DAX Measures

Created the following DAX measures:

**Total Sales**
```dax
Total Sales = SUM(Orders[Sales])
```

**Total Profit**
```dax
Total Profit = SUM(Orders[Profit])
```

**Profit Margin**
```dax
Profit Margin = DIVIDE([Total Profit], [Total Sales], 0)
```

### 4. KPI Cards
Created three KPI cards to display:
- Total Sales
- Total Profit
- Profit Margin

### 5. Slicers
Added interactive slicers for:
- Region
- Year

### 6. Data Visualization
Created the following visualizations:
- Sales by Region – Bar Chart
- Profit by Category – Column Chart
- Monthly Sales Trend – Line Chart
- Profit Analysis – Table

### 7. Conditional Formatting
- Highlighted negative profit values in red.
- Highlighted positive profit values in green.
- Used conditional formatting to identify loss-making categories and regions.

## Dashboard Overview
The final dashboard provides an overview of retail store performance through KPI cards, interactive filters, sales and profit charts, and profit analysis.

## Key Learnings
- Understanding DAX functions and measures.
- Creating KPI cards in Power BI.
- Building interactive dashboards using slicers.
- Establishing relationships between multiple tables.
- Applying conditional formatting.
- Analyzing sales and profit performance.

## Project File
`Week3_Retail_KPI_Dashboard.pbix`

## Conclusion
This assignment helped develop practical skills in Power BI, DAX calculations, data modeling, and interactive dashboard creation for business intelligence and retail sales analysis.
