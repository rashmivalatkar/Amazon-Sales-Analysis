# Amazon-Sales-Analysis

Overview:-

This Power BI report provides a comprehensive and actionable view of Amazon product performance across the year. It integrates sales, profitability, and customer feedback into a single, interactive dashboard, enabling stakeholders to quickly identify growth opportunities and areas of concern.


Project Objectives: The objective is to implement a Power BI dashboard that delivers a unified, data driven view of Amazon Product performance.

•	Track and visualize revenue performance across Year to Date (YTD) and Quarter to Date (QTD) periods.

•	Highlight product level sales contributions to identify top performers and underperforming items.

•	Analyse profitability trends to determine whether overall profit margins are increasing or declining.

•	Incorporate customer review data to assess sentiment and its correlation with sales outcomes.


Tools & Technologies Used: -

•	Power BI Desktop

•	DAX (Data Analysis Expressions)

•	Power Query (ETL)


Data Processing:

•	Amazon Products Sales data imported into Power BI

•	Data cleaning and transformation performed using Power Query Editor

•	Steps included – Data type validation, handling missing or inconsistent records

•	Creating calculated columns as required.


Data Model:

•	Fact Tables represents Sales facts and Review facts using metrics and key indicators

•	Dimension tables support attributes like Product ID, Product category, product description.

•	Relationships are created using correct cardinality to ensure accurate KPIs and chart outputs.

•	Cross filter direction is configured to ensure correct aggregations. It determines how filters flow between related tables, and when set properly, it guarantees that KPIs and charts aggregate values accurately without duplication or distortion.


Measures & Calculations:-

•	Business logic implemented using DAX measures

•	Measures include like YTD Sales, QTD sales, YTD Product sold and YTD customer reviews.

•	Measures are reusable across multiple report visuals.


Reports Features:

•	KPI cards for high- level management metrics.

•	Bar and column charts to show month and weekwise comparisons

•	Line charts for trend analysis

•	Tables and matrix for detailed insights

•	Slicers/filters for interactive filtering.

Business Insights:

•  YTD and QTD tracking reveals clear revenue growth patterns and seasonal trends.

•	Top performing products drive majority of sales; underperformers highlight areas for improvement.

•	Customer sentiment strongly correlates with sales outcomes, reinforcing the impact of reviews.

•	Negative reviews act as early warning signals for potential sales decline.

<img width="1265" height="710" alt="image" src="https://github.com/user-attachments/assets/99f9277e-63c9-4c5d-86ce-3e8b716afd00" />

•	Clean ETL processes ensure reliable, consistent reporting for decision making.
•	Correct cardinality and cross filter setup guarantee accurate KPIs and visualizations.
•	Dashboard empowers stakeholders with actionable insights for growth and risk mitigation.



