# Insurance Analysis: Driving Profitability and Efficiency with Power BI

![Alt text for the image](https://github.com/Hammed-Hassan/Insurance_Data_Analysis___Power-BI/blob/main/Front%20Page.png)

#
## ✅Executive Summary
This project, developed as part of a Power BI bootcamp, tackles the business challenge of fluctuating profitability and rising costs in an insurance company. Through a comprehensive dashboard, the analysis provides insights into claims, customer behavior, and policy performance to guide strategic decisions and improve customer retention.

#
### ✅Business Problem
The core objectives of this analysis were to address the following key business questions:
- Identify the root causes of rising claims costs and lengthy processing times.
- Determine the profitability of policies across different customer segments.
- Understand the key factors influencing customer churn and retention.
- Detect anomalous patterns that could indicate fraudulent activity.

#
### ✅Data Sourcing 
This dataset was provided by the online school under strict confidentiality agreements and is classified as proprietary information. As such, it cannot be shared with third parties without explicit authorization.

#
### ✅Data Tranformation & Manipulation
### Data Cleaning with Power Query
- I handled missing values by removing and replacing all the null and blank data.
- I corrected the data types to ensure all columns were in the right format, and I set the first row as the column headers.
- I renamed columns for clarity and restructured the data using merges and splits to organize it.
- My changes were also documentated so anyone can see the changes of my work.
### Measures (DAX)
Dynamic measures were created with DAX to perform aggregations for key business metrics. These calculations respond to filters and slicers in the report. Few measures are shown below

  ![Alt text for the image](https://github.com/Hammed-Hassan/Insurance_Data_Analysis/blob/main/I1.png)
  - Purpose: Calculating the total revenune unaffected by any filters.

  ![Alt text for the image](https://github.com/Hammed-Hassan/Insurance_Data_Analysis/blob/main/I2.png)
  - Purpose: Calculating the percnetage of each sales mode.
    
  ![Alt text for the image](https://github.com/Hammed-Hassan/Insurance_Data_Analysis/blob/main/I3.png)
  - Purpose: Calculating the total amount of policies from Online Agent.
#
### Data Modelling 
A star schema data model was implemented to create a robust and scalable structure. This model centered around a fact premiums and settlements table, which was linked to several dimension tables including Customers, Policies, and Calendar. This design allows for efficient cross-functional analysis and provides a foundation for complex DAX measures.

![Alt text for the image](https://github.com/Midoford/Insurance-Data-Analysis-Dashboard/blob/main/201.png)


# 
### ✅Dashboard Design
### General View
![Alt text for the image](https://github.com/Midoford/Insurance-Data-Analysis-Dashboard/blob/main/202.png)
### Sales Mode Analysis View
![Alt text for the image](https://github.com/Midoford/Insurance-Data-Analysis-Dashboard/blob/main/203.png)
### Age Group Analysis View
![Alt text for the image](https://github.com/Midoford/Insurance-Data-Analysis-Dashboard/blob/main/204.png)

# Live Dashboard - [link](https://app.powerbi.com/view?r=eyJrIjoiMWM4MDM5NzItZDZkZS00NDUyLTliMDMtYzg5Njc1ZjE1ZjdhIiwidCI6IjAwMGRiMTM4LTRjODAtNDc0MC04NDY4LTFiYmMxN2Y5ZTNlYSJ9)

### ✅Analysis & Key Insights
- Following March 2023's significant customer acquisition spike, both Total Revenue ($33.12bn) and Total Customer (19.03k) experienced a slight 1% decline month-over-month.
- The 31-40 age group is the largest and highest-revenue customer segment ($12.31bn), with Delhi NCR dominating city performance at $13.31bn total revenue.
- The Offline-Agent sales mode overwhelmingly dominates, accounting for over 55% of both total customers and revenue; however, all sales channels experienced a universal revenue surge in March 2023 followed by a sharp decline in April 2023.

#
### ✅Conclusion & Recommendation 
Conclusion
The "Insurance Analysis" project successfully delivered a comprehensive solution for the company's data challenges. The Power BI dashboard provides a single source of truth for financial performance, customer behavior, and operational metrics.
- Following a significant customer acquisition spike in March 2023, both Total Revenue ($33.12B) and Total Customers (19.03k) experienced a slight 1% month-over-month decline.
- The 31-40 age group is the largest and highest-revenue customer segment, with Delhi NCR being the top-performing city.
- The Offline-Agent sales channel is the primary revenue driver, but all sales channels experienced a universal revenue surge in March 2023 followed by a sharp decline in April 2023.

#
### ✅Recommendation
- Strategically Refine Channel Mix: Investigate the universal revenue decline in April 2023 to identify the root causes and develop a more resilient, diversified sales channel strategy.
- Optimize High-Performing Segments: Leverage the insights from the dominant 31-40 age group and the Delhi NCR region to develop targeted marketing campaigns and policy offerings to maximize lifetime value.
- Proactively Manage Claims: Use the granular claims data to identify process bottlenecks and implement measures to reduce processing times and associated costs.
- Enhance Fraud Detection: Implement a dedicated fraud detection workflow using the project's data foundation to monitor for and flag anomalous claims.

# 
### ✅Technical Skills and Tools
- Data Visualization: Power BI
- Data Wrangling & ETL: Power Query
- Analysis: DAX (Data Analysis Expressions)
- Modeling: Star Schema
- Conceptual: Statistical Analysis, Customer Segmentation

![Alt text for the image](https://github.com/Hammed-Hassan/AtliQ_Consumer_Electronics_Analysis/blob/main/istockphoto-1397892955-612x612.jpg)



