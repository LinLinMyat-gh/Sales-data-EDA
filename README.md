# SQL Exploratory Data Analysis - Sales Dataset
## Project Overview
For this project, I adopted a structured data analytics framework to guide the exploration process. This framework covers key analytical techniques such as database exploration, measures analysis, ranking, trend analysis, cumulative analysis, performance analysis, and reporting.

By following this framework, I was able to investigate the dataset and identify significant pattern.

### 1. Database Exploration
I began by exploring all tables within the database using the INFORMATION_SCHEMA.TABLES view. 
<img width="902" height="111" alt="image" src="https://github.com/user-attachments/assets/775053f2-7894-4ecf-95a5-a414db98c155" />


Next, I examined the columns and data types within the customer dimension table using INFORMATION_SCHEMA.COLUMNS which made me see the details of the schema, relevant fields for analysis and the data available in each table.
<img width="898" height="105" alt="image" src="https://github.com/user-attachments/assets/1d40c021-28df-40c4-9f8f-6653cb34eb15" />

### 2. Dimension Exploration
Now, it's time to explore the key dimensions in the dataset to understand the available categories and segments such as customer countries, product categories, subcategories  and individual products.
<img width="892" height="413" alt="image" src="https://github.com/user-attachments/assets/df091c6e-4633-42ca-a873-afda4d7a4a35" />

### 3. Date Exploration
I explored the date-related fields such as identifying the first and last order dates with MIN() and MAX(), calculating the number of years of sales data by substracting  and analyzing customer birthdates to know their age range with TIMESTAMPDIFF().
<img width="895" height="262" alt="image" src="https://github.com/user-attachments/assets/8c7864c3-afd3-4620-a95d-397932407c4b" />



### 4. Measures Exploration
To understand baseline KPIs of the dataset, i used aggregate functions to calculate total sales, total quantity sold, average selling price, total orders, total products and total customers etc. 


### 5. Magnitude Analysis
This step is about measuring the size and scale of business metrics across different dimensions using (Aggregate functions and GROUP BY). This Identified the countries, customer segments, product categories, and customers that contribute the most to sales and revenue.

### 6. Ranking Analysis

- Which 5 products generate the highest revenue? Using CTE
<img width="897" height="293" alt="image" src="https://github.com/user-attachments/assets/df7bfecb-eb47-4cbd-89a9-4e93b0382fd0" />


- Finding the top 10 customers who generated the highest revenue. Using Subquery
  <img width="912" height="300" alt="image" src="https://github.com/user-attachments/assets/73aa7f8b-218e-48bc-aed2-fb53ab367816" />

## Conclusion


The project highlights the importance of exploratory analysis as a first step in any data analytics workflow helping to uncover insights and guide future business decisions.







