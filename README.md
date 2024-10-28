# LITA-CAPSTONE-PROJECT
I will be analyzing two data which are sale data of a retail store and customer data on subscription

### Project Overview
The aim of this project is to analyze the sales performance of a retail store by exploring key metrics such as top-selling products, regional sales performance, and monthly sales trends. Additionally, the project analyzes customer data from a subscription service to identify customer segments and emerging trends. Through this analysis, actionable insights will be derived to support strategic business decisions.

### Data Source
The dataset used for this analysis was provided by Incubator Hub, an educational technology organization. The data includes sales records from a retail store and customer information from a subscription service, specifically curated for educational purpose

### Tools Used
1. Microsoft Excel
   - Data cleaning and preparation.
   - Utilized Excel formulas to calculate key metrics such as average (AVG) and total sales.
   - Created data visualizations using pivot tables to identify trends and insights.

2. SQL- Structured Query Language
   - Extracted key insights by writing queries to filter, group, and analyze the data.
   - Used SQL to perform data manipulation and retrieve specific information for further analysis.

3. Power BI
   - Built interactive dashboards to visualize sales performance and customer data.
   - Performed data cleaning and transformation to ensure accurate visual representation.
   - Created detailed visualizations to highlight regional performance, top-selling products, and customer segmentation.

### Data Cleaning and Preparation
1. Data Loading and Inspection
   
    a. Microsoft Excel:
      - Imported the dataset into Excel and expanded the worksheet table to inspect all data fields.
      - To check for duplicates: Highlighted the entire table.
      - Clicked on the Data tab and selected Remove Duplicates to identify and eliminate any redundant records.
        
    b. SQL Server:
       - Imported data by creating a new database in SQL Server
       - Created a database, right-clicked on it, and selected Import Data to load the dataset.
       - Used SQL commands to remove excess columns and rows directly:
       - To delete unnecessary columns and to delete rows with missing CustomerID values.
   
    ```SQL
    ALTER TABLE [dbo].[LITA Capstone Dataset_Ruth] DROP COLUMN column10;
    

```SQL 
DELETE FROM [dbo].[LITA Capstone Dataset_Ruth] WHERE CustomerID IS NULL;




   
