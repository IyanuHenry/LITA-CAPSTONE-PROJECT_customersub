# LITA-CAPSTONE-PROJECT
project work

### Project Overview
The goal is to analyze customer data for a subscription service to identify segments and trends that influence customer retention and spending behavior.

### Data Source
The source of the data was provided by Incubator Hub, which is an educational tech platform.

### Tools Used
1. Microsoft Excel
   - Data cleaning and preparation.
   - Utilized Excel formulas to calculate key metrics such as such as subscription duration =DAYS(SubscriptionEnd,SubscriptionStart) and average Revenue =AVERAGE(Revenue).
   - Created data visualizations using pivot tables to segment customer data.

2. SQL- Structured Query Language
   - Extracted key insights by writing queries to analyze customer demographics and spending patterns.
   - Cleaned data by handling null values and unnecessary columns.

3. Power BI
   - Developed dashboards to visualize customer behavior metrics.
   - Cleaned and transformed data for effective visualization.

### Data Cleaning and Preparation
1. Data Loading and Inspection
   
   a. Microsoft Excel:
      - Imported customer data, expanded the worksheet table, and checked for duplicates.
   
   b. SQL Server:
      - Created a database, imported customer data, and removed unnecessary columns and rows.
        
   c. Power BI:
      - Imported data and checked column distributions to identify duplicates and blanks.
   
      ```SQL
      ALTER TABLE [dbo].[LITA Capstone Dataset_Ruth] DROP COLUMN column10;
      DELETE FROM [dbo].[LITA Capstone Dataset_Ruth] WHERE CustomerID IS NULL;
      ```
   
![Excel duplicate](https://github.com/user-attachments/assets/54c4f976-30f5-477e-a4de-e7eb0ff430a4)


![Drop and delete](https://github.com/user-attachments/assets/35e32130-8367-477d-b9df-924e9897206c)

2. Handling Missing Variables

   a. Microsoft Excel:
      - Added a column for subscription duration to analyze retention rates.

   b. SQL- Sturctured Query Language:
      - Used IS NULL to locate missing values and deleted rows with null CustomerID.
        
   c. Power BI:
      - Used transformation tools to manage missing values effectively.  
        

3. Data Cleaning and Formatting

   a. Microsoft Excel:
    - Standardized formats for subscription dates and customer details. 
  
   b. SQL:
      - Checked and adjusted data types to ensure uniformity.
   
   c. Power BI:
      - Applied consistent formats and renamed columns as necessary.

### Data Analysis Process

The data analysis process for the subscription service customer data aimed to uncover customer behaviors and retention trends.

1. Data Exploration
   - Initial Review: Reviewed customer data to understand its structure and identify variables related to customer demographics, subscription durations, and spending.

2. Descriptive Statistics
   - Subscription Duration Calculation: Calculated the subscription duration in Excel, providing insights into customer retention and loyalty patterns.
  
3. Customer Segmentation
   - Demographic Analysis: Segmented customers based on demographics and subscription behaviors, employing SQL queries to categorize customers into meaningful segments (e.g, geographic locations).
   - Lifetime Value Calculation: Estimated customer lifetime value (CLV) by analyzing subscription duration and average spending, informing retention strategies.
     
3. Trend Analysis
   - Retention Trends: Analyzed retention rates over time using line graphs in Power BI to identify periods of high churn and evaluate the effectiveness of retention initiatives.
   - Spending Patterns: Examined spending trends among different customer segments, employing scatter plots and bar charts to visualize correlations between subscription duration and spending.

4. Insights Generation
   - Actionable Insights: Derived actionable insights, such as identifying high-value segments that require tailored marketing efforts and strategies to improve retention rates among at-risk customers.
   - Reporting: Presented findings in a comprehensive report format, including visualizations to support recommendations for enhancing customer engagement and retention strategies.








   
