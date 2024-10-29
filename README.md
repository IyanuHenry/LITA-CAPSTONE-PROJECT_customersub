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
   
   c. Power BI:
     - Loaded the data via the Get Data option and entered Power Query Editor;
     - Examined the column distribution by selecting Column Quality and Column Distribution to check for duplicates, blanks, and unique values.
     - Used Remove Duplicates and Transform Data to further clean the dataset.
   
      ```SQL
      ALTER TABLE [dbo].[LITA Capstone Dataset_Ruth] DROP COLUMN column10;
      DELETE FROM [dbo].[LITA Capstone Dataset_Ruth] WHERE CustomerID IS NULL;

   
![Excel duplicate](https://github.com/user-attachments/assets/54c4f976-30f5-477e-a4de-e7eb0ff430a4)


![Drop and delete](https://github.com/user-attachments/assets/35e32130-8367-477d-b9df-924e9897206c)

2. Handling Missing Variables

   a. Microsoft Excel:
      - Added columns to support further analysis and fill in essential metrics:
      - Sales Revenue: Used the formula =SUM(Quantity * Unit Price) in a new column to calculate sales revenue for each entry in the retail store data.
      - Subscription Duration: Added a column to calculate the duration of each subscription in the subscription service dataset.
      - Ensured all calculations were complete to support downstream analysis.
   
   b. SQL- Sturctured Query Language:
      - Used the IS NULL function to locate and handle missing values in key fields.
      - Deleted rows with null values in critical fields, such as CustomerID, ensuring data integrity for further analysis.
   
   c. Power BI:
      - In the Power Query Editor, used tools to fill, replace, or remove null values as necessary.
      - Added calculated columns when required to address missing data, ensuring consistent and reliable metrics across datasets.
        
![Screenshot (71)](https://github.com/user-attachments/assets/95142c69-ccd6-4e8b-b49c-abedaf167a28)


3. Data Cleaning and Formatting
   a. Microsoft Excel:
    - Standardized formats for fields such as dates, currency, and text case. Utilized tools like Text-to-Columns and Find & Replace for consistent formatting.
    - Ensured that all relevant columns were formatted correctly to facilitate accurate calculations and visualizations, such as using currency formatting for sales figures and date 
      formatting for any date fields.





   
