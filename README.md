
### MyLITA-Finals
### Project Title: Customer Segmentation for a Subscription Service

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Explanatory Data Analysis](#explanatory-data-analysis)

[Data Analysis](#data-analysis)
![SQL](https://github.com/user-attachments/assets/1ccfff80-02c1-4149-bbe7-1b96cda7dae8)

[Data Visualization](#data-visualization)

[Inference](#inference)

## Project Overview
---
The aim of this project is to analyze customer data for a subscription service to identify segments and trends within two years. The goal is to understand customers behavior, track subscription types, and identify key trends in cancellations and renewals of the subscribed services.

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
```DAX
Count True = COUNT ROWS(FILTER(CustomerData1,CustomersData1[Cancellation]=True))
```

## Data Visualization
![For CustomerData](https://github.com/user-attachments/assets/66222de8-f628-4af0-b908-b8b3eab14779)

![Updated](https://github.com/user-attachments/assets/b1b8f020-d715-4adf-83a9-7a7294d01782)



## Inference
1. The total numbers of Subscribers that cancelled were approximately 34,000 which means Renewals were approximately 41,000.
2. Subscription is are the peak at the beginning of the year, but drops by the end of the year.
3. The East and the North Regions subscribe to the Basic type only, while Premium is available only in the South Region and Standard only in the West Region.

## Recommendations
1. There is the need to focus on the Marketing Strategies and Wide Coverage, why some type are predominant in one Regon and none at all in the other Regions.
2. Promotional Sales should be carried out in all the four Regions and good incentives should be provided.
3. Coverage areas should be greatly increased in all the four regions to tackle the issue of good connectivity in all the regions.
4. There should be special Promotional Sales towards the end of the year to encourage more and stable subscriptions.

Thank you.
