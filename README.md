# LITA-CAPSTONE-PROJECT
project work

### Outline
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Data Cleaning and Preparation](#data-cleaning-and-preparation)
- [Data Analysis Process](#data-analysis-process)
- [Data Visualization](#data-visualization)
- [Insights and Findings](#insights-and-findings)
- [Conclusion](#conclusion)

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
  
     ![subDuration](https://github.com/user-attachments/assets/d32ef22d-5888-48b4-ad51-0cf8487e1edc)

     
3. Trend Analysis
   - Retention Trends: Analyzed retention rates over time using line graphs in Power BI to identify periods of high churn and evaluate the effectiveness of retention initiatives.
   - Spending Patterns: Examined spending trends among different customer segments, employing scatter plots and bar charts to visualize correlations between subscription duration and spending.

4. Insights Generation
   - Actionable Insights: Derived actionable insights, such as identifying high-value segments that require tailored marketing efforts and strategies to improve retention rates among at-risk customers.
   - Reporting: Presented findings in a comprehensive report format, including visualizations to support recommendations for enhancing customer engagement and retention strategies.
  
### Data Visualization
 Data visualization revealed key patterns in customer behavior and retention.

1. Interactive Trends Analysis
   - Demographic Insights: Pie charts visualizing the proportion of different demographic segments among subscribers.
   - Retention Dashboard: Metrics showcasing churn rates and renewal patterns over time.
   - Subscription Type Visualization: Pie chart showing the distribution of subscription types.
   - Revenue by Region: Bar chart for the sum of revenue by region.
   - Active Customers Visualization: Bar chart visualizing the number of active customers.

![Subpivottable](https://github.com/user-attachments/assets/7f7a18a1-9421-404b-9a55-8ba0ebd06987)

![Screenshot (91)](https://github.com/user-attachments/assets/3aea77da-09f1-4b70-8cd0-76e8fcdf4177)

2. Customer Segmentation Dashboard in Power BI
   
   -  Demographic Breakdown: Create a bar chart visual that categorizes customers by location (e.g., East, South, North, West).
      This chart would provide an overview of customer demographics, helping you identify the regions where most customers are based.
   
   -  Subscription Duration Trends: Use a line graph to plot average subscription duration over time.
      This will help in tracking retention trends, showing how long customers typically stay subscribed, and indicating any seasonal or time-based patterns.
   
   -  Renewal Rates Visualization: Design a stacked bar chart that segments renewal rates by customer demographics (e.g., region, subscription type).
      This visualization could show the proportion of renewals versus cancellations within each segment, offering insights into customer loyalty across different demographics.
   
   -  Customer Spending Patterns: Implement a scatter plot to display the relationship between subscription duration and average spending per customer.
      This scatter plot can reveal any correlation between how long customers stay subscribed and their spending levels, potentially highlighting high-value, long-term subscribers.

      ![Screenshot (101)](https://github.com/user-attachments/assets/c7577ece-c8cb-4e9b-844d-ba5870da54ad)

      ![Screenshot (102)](https://github.com/user-attachments/assets/26dc185b-d84b-497f-9f99-848a7411ebc6)

      ![Screenshot (105)](https://github.com/user-attachments/assets/ee2ae853-6cc3-4ff9-be64-b10bfc068bbc)


### Insights and Findings
 - High-Value Customer Segments: East region exhibit higher average spending, indicating potential target markets for tailored marketing efforts.
   
 - Retention Opportunities: The analysis highlighted segments with lower renewal rates, prompting further investigation into customer satisfaction and potential areas for service improvement.
   
 - Subscription Preferences: Insights from the subscription type pie chart indicate basic type among customers, which can guide future service offerings and pricing strategies.
   
 - Geographic Performance: The revenue in the East region revealed strong performance, suggesting opportunities for expanding marketing efforts in underperforming regions especially West.
   
 - Active Customer Trends: The high number of active customers indicates the effectiveness of retention strategies and strong overall customer engagement.

### Conclusion
The analysis of subscription customer data highlights key insights into customer behavior and retention strategies. The East region shows higher average spending, presenting opportunities for targeted marketing. Retention analysis reveals segments with lower renewal rates, indicating a need for improved customer satisfaction. The preference for basic subscription types guides future service offerings, while strong revenue performance in the East suggests potential for expanding efforts in underperforming regions, especially the West. Overall, the high number of active customers reflects the effectiveness of current retention strategies and strong customer engagement.







   
