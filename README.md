
### MyLITA-Finals
### Project Title: Customer Segmentation for a Subscription Service

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Explanatory Data Analysis](#explanatory-data-analysis)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Inference](#inference)





## Project Overview
---
The aim of this project is to analyze customer data for a subscription service to identify segments and trends. The goal is to understand customers behavior, track subscription types, and identify key trends in cancellations and renewals of the subscribed services.

## Data Sources
---
The primary source of Data used is the LITA Capstone Project .xslx

## Data tools used
---
- Microsoft Excel [Download here](https://www.microsoft.com)
  1. For Data Cleaning
  2. For Data Analysis
  3. For Visualization
- Structured Query Language for quering Data [Download here](https://www.microsoft.com/en-us/sql-server)
- Power Business Intelligence for visualization and connecting data across different dashboards [Download here](https://powerbi.microsoft.com)
- Github for portfolio building

## Data Cleaning and Preparation
---
At the beginning of Data Cleaning and Preparation, the following steps were taken.
 1. Data loading and Inspection
 2. The Data used is clean.

## Explanatory Data Analysis 
---
This includes exploring of data to track subscription types, and identify key trends in cancellations and renewals of the subscribed services.

## Data Analysis
---
This includes some basic lines of queries

```SQL
SELECT 
    Region, 
    COUNT(CustomerID) AS TotalCustomers
FROM 
    CustomerData
GROUP BY 
    Region;
```
## Data Visualization



## Inference
