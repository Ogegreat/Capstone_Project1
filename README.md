# Capstone_Project1
This Project was carried out to Analyse retail store sales dataset to discover key insights on the retail store sales performance and its turnover. 

## Project Topic: Sales Performance Analysis for a Retail Store

### Project Overview 
In this project an insights were drawn from the dataset to understand the retail store sales performance.  Performing data analysis using powerful analytic tools such as 
 Excel, PowerBI to uncover the products that had increased the retail store sales, the Regions with highest increase in sales. This helps the retail store to discover what best they are doing and areas that need to be improved on. 

 ### Data Sources
  The primary data used was  MicroSoft Excel file sourced from Online platform, Learning Management System (LMS) which was open to the registered students.

### Tools Used[Download Here](https://www.microsoft.com)
- Microsoft Excel
  1. Microsoft Excel was used for cleaning the data.
  2. It was used in analysis of the data.
  3. Visualization of the data.

- Power BI
  1. Power BI was used in Analysing the data.
  2. It was used to perform Data Analysis Expression such getting Measures.
  3. Visualization of the data.
 
  - Structured Query Language
    1. Structured Query language (SQL) was  used to query the data. This helped to get the retail sales amount, revenue generated, product that made highest sales etc.

  - Git Hub
    1. Git hub was used in Portfolio building.
    2. It was used for group collaboration.
   
  ### Data Cleaning And Preparations
  In this Stage the  following processes were done;
  1. Data was loaded into analytic tools such as MicroSoft Excel and checked.
  2. Checking data type, missing values.
  3. Data cleaning and formatting.
  4. Data profiling.
 
  ### Exploratory Data Analysis
  Exploratory Data Analysis entails explorying the data to get answers to the questions of the stakeholders such as;
  - what is the sales overview trends
  - What is the total sales of the product.
  - Which Product has the highest sales.
  - What is the total revenue
  -  Which month was the highest sales made.

  ### Data Analysis
  Some SQL Server codes and Data Analysis Expression in Power BI  used in fetching the insights from the data are written below;
  ```SQL
  SELECT Product, sum(Quantity) as TotalQuantity FROM CapstoneDataset group by Product
select * from CapstoneDataset
```

```SQL
Select Product, Region sum(Quantity) As NumberSalesTransaction From CapstoneDataset 
group by Product,  Region

```
```SQL
select Product, sum(Quantity*UnitPrice) As TotalRevenue
from CapstoneDataset group by product
```
```DAX
AverageSales= Average(sum(CapstoneDataset[Quantity])
```

### Data Visualization
The following visual that draws the insights from the data are displayed below;

![image](https://github.com/user-attachments/assets/8cf17b68-a72e-4385-b413-f95b87de2ecd)

     
