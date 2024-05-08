# GOOGLE FIBER: Analyzing Repeated Customer Calls Across Markets and Types

## Objective:
The objective of this project is to analyze repeated customer calls across different markets and types of issues to identify patterns, trends, and insights that can inform strategic decision-making for improving customer service and operational efficiency.

## Data Sources:
Three Excel files containing customer call data across different markets and types of issues.

## Tools and Skills:
- **Excel:** Data loading, data type manipulation, data extraction, data cleaning, and preparation.
- **Power Query:** Data transformation including extracting month, week, quarter, and day, removing empty rows, and replacing null values.
- **Tableau Public:** Data visualization, merging multiple Excel sheets, creating calculated fields, generating various types of charts (column charts, pie charts), applying filters, and formatting tooltips.

## Project Steps:

## Excel:
1. **Load Data in Power Query:** Import data from Excel files into Power Query for further processing.
2. **Data Type Transformation:** Change data types as necessary for columns such as 'date' to ensure consistency and accuracy in analysis.
3. **Extract Time Components:** Extract month, week, quarter, and day from the 'date' column to facilitate time-based analysis.
4. **Remove Empty Rows:** Eliminate rows with empty values in columns like 'market' and 'type' to enhance data quality.
5. **Replace Empty Values:** Replace null values with 0 in the 'contact_n_#' column to maintain data integrity.
6. **Repeat Data Cleaning:** Apply the same data cleaning steps to all files, ensuring consistency across datasets.
7. **Standardize Column Names:** Standardize column names such as changing "market_1" to "Market 1" for improved clarity and readability.
8. **Sheet Renaming:** Rename sheets to "Market_1," "Market_2," and "Market_3" for easy identification and organization.
9. **Save as Excel Workbook:** Save the cleaned and processed data as an Excel workbook for further analysis.

## Tableau:
1. **Load Excel Workbook:** Import the cleaned Excel workbook into Tableau Public.
2. **Merge Excel Sheets:** Merge multiple Excel sheets using union to create a unified dataset for analysis.
3. **Create Calculated Fields:** Generate calculated fields such as "Total repeated calls" by aggregating 'contact_n_#' columns across different markets and types.
4. **Visualizations - Day 0 Calls and Repeat Calls:** Create a dual-axis chart showing day 0 calls and repeat calls by market type, using columns like 'new_market', 'day', 'contact_n', and 'total repeated calls'.
5. **Visualizations - Total Repeated Calls by Type:** Design visuals illustrating total repeated calls by type, including pie charts and column charts, utilizing columns like 'new_type', 'contact_n', and 'total repeated calls'.
6. **Apply Filters:** Apply filters based on month and day to analyze data across different time periods, using columns like 'month' and 'day'.
7. **Tooltip Formatting:** Enhance visualization clarity by formatting tooltips to provide additional context and insights.

------------------------------------------------

Info About Data:
- Type_1: Account Management
- Type_2: Technician Troubleshooting
- Type_3: Scheduling
- Type_4: Construction
- Type_5: Internet and WiFi

------------------------------------------------

## Analysis Findings:

1. **Market-wise Distribution of Repeated Calls:**
   - Market 1 received the highest percentage of repeated calls across all months, accounting for approximately 63% of total repeated calls, followed by Market 3 with 34%. Market 2 received the least, representing only 4% of the total repeated calls.

2. **Distribution of Repeated Calls by Issue Type:**
   - Type 5, related to Internet and WiFi issues, received the highest percentage of repeated calls, comprising around 51% of the total repeated calls. Type 2, involving Technician Troubleshooting, followed closely behind with 30%. Type 4, associated with Construction issues, received the least, accounting for only 1% of the total repeated calls.

3. **Prevalence of Repeated Calls Across Markets:**
   - Across all markets, Type 2 (Technician Troubleshooting) and Type 5 (Internet and WiFi) consistently experienced the highest volume of repeated calls, indicating these issues as recurring challenges for customers.

4. **Timing of Repeated Calls:**
   - The majority of repeated calls across all markets occurred on day 1, following the initial contact (day 0). This suggests that customers often encounter issues shortly after their initial interaction, highlighting the need for efficient resolution processes.

5. **Day-wise Distribution of Repeated Calls:**
   - In Market 1 and Market 2, the highest volume of repeated calls was observed on Mondays, while Market 3 experienced the peak on Wednesdays. This insight into weekly patterns can aid in resource allocation and scheduling to address the influx of repeated calls effectively.

## Conclusion:
Through rigorous data cleaning, analysis, and visualization in Excel and Tableau, this project provides actionable insights into customer call patterns, enabling informed decision-making to enhance customer satisfaction and operational efficiency across diverse markets and issue types.
