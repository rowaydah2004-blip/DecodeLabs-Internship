\# DecodeLabs Project 2: Exploratory Data Analysis (EDA)



\## Project Overview

This project was completed as part of my Data Analytics Internship at DecodeLabs. The objective was to perform exploratory data analysis on an e-commerce orders dataset using Microsoft Power BI, identify patterns and trends, calculate descriptive statistics, and investigate potential outliers.



\## Tools Used

\- Microsoft Power BI Desktop

\- Power Query

\- DAX (Data Analysis Expressions)

\- Microsoft Excel



\## Dataset

The dataset contains 1,200 order records, including order IDs, dates, customer IDs, products, quantities, unit prices, total prices, order statuses, payment methods, and referral sources.



\## Analysis and Visualizations



\### 1. Descriptive Statistics

Created KPI cards showing:

\- Total Orders: 1,200

\- Average Order Value: 1,053.97

\- Median Order Value: 823.62

\- Minimum Order Value: 11.39

\- Maximum Order Value: 3,456.40



\### 2. Product Analysis

Compared total sales across product categories using a horizontal bar chart. Chairs and printers generated the highest sales totals, while phones generated the lowest among the seven categories.



\### 3. Sales Trends

Analyzed sales over time using a monthly line chart covering 2023 to 2025. Monthly sales fluctuated, with notable peaks and declines.



\### 4. Order Analysis

Examined order distribution across order statuses using a donut chart and compared payment-method frequency using a column chart.



\### 5. Order Value Distribution and Outlier Detection

\- Created an order value distribution chart using bins of 250.

\- Used quartiles and the interquartile range (IQR) to calculate outlier boundaries.

\- Identified 8 potential outlier orders, approximately 0.67% of the dataset.

\- Created an outlier details table showing the relevant order IDs, values, dates, and products.



\## Key Findings

\- Order values are right-skewed, with more orders concentrated in lower value ranges.

\- The average order value (1,053.97) is higher than the median (823.62).

\- Chairs and printers contributed the highest total sales among the displayed product categories.

\- Sales varied across months and years.

\- Eight orders were flagged as potential outliers using the IQR method. These should be reviewed before any data correction or removal.



\## How to Run

1\. Download `DecodeLabs\_Project2\_EDA.pbix` from this repository.

2\. Install Microsoft Power BI Desktop if it is not already installed.

3\. Open the `.pbix` file in Power BI Desktop.

4\. Explore the five report pages and their visualizations.

5\. If a refresh is necessary, download `Dataset for Data Analytics (1).xlsx` and update the source path in Power Query to its location on your computer.

6\. Apply changes and refresh the report.



\## Project Files

\- `DecodeLabs\_Project2\_EDA.pbix`: Power BI report and analysis.

\- `Dataset for Data Analytics (1).xlsx`: Source dataset.

\- `README.md`: Project documentation.



\## Conclusion

This project strengthened my skills in descriptive statistics, data visualization, DAX measures, trend analysis, and outlier detection using Power BI. The findings demonstrate how exploratory analysis can support a better understanding of order behavior and data quality.



\## Internship

DecodeLabs Data Analytics Internship | October 2026



