This repository contains a comprehensive data analysis of a UK-based online retailer's transactional data. The project aims to provide data-driven insights into sales trends, customer behavior, and product relationships to inform strategic business decisions. The final analysis is presented in an interactive R Markdown report.

Key Findings Identified Sales Trends: The analysis revealed a strong seasonal pattern, with sales significantly peaking in December.

Customer Segmentation: Customers were successfully segmented into actionable groups (e.g., "High-Value," "Loyal," and "At-Risk") using the RFM (Recency, Frequency, Monetary) model.

Data Quality Issues: The initial dataset contained a high number of invalid transactions, including negative quantities and zero unit prices, which were cleaned for accurate analysis.

Market Basket Analysis: Association rules were generated to identify which products are most frequently purchased together, providing insights for product bundling and recommendation engines.

Methodology: The analysis was performed in R following a structured process:

Data Cleaning: Removed invalid transactions and handled missing values.

Data Transformation: Converted data types (e.g., character to datetime) and created new features like TotalSales.

Feature Engineering: Calculated RFM scores and customer lifetime value (CLV).

Exploratory Data Analysis (EDA): Utilized ggplot2 to visualize sales trends and customer behavior.

Customer Segmentation: Applied case_when to assign customers to segments based on their RFM scores.

Tools & Technologies R

RStudio

tidyverse (dplyr, ggplot2, lubridate, tidyr)

arules and arulesViz (for Market Basket Analysis)
