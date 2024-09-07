# Data Professional Survey Analysis

### Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning / Preparation](#data-cleaning-preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results/Findings](#results-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [References](#references)


### Project Overview

This data analysis project aims to provide insights into the data professional jobs using the survey data collected. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of the company's performance.

![survey project](https://github.com/user-attachments/assets/49345403-0daf-4fa9-b79b-2f355fd7cac7)


### Data Sources

Survey Data: Data consists of the data gathered from the online survey conducted to collect information about their jobs and related information from the data professionals.

Dataset: [Dowload Here](https://github.com/AlexTheAnalyst/Power-BI/blob/main/Power%20BI%20-%20Final%20Project.xlsx)

### Tools

- Power Bi

### Data Cleaning / Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- What is the overall sales trend?
- Which products are top sellers?
- What are the peak sales periods?

### Data Analysis

```sql
SELECT * FROM table_name where condition1 = 2;
```

### Results/Findings

The analysis results are summarized as follows:

- The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
- Product Category A is the best-performing category in terms of sales and revenue.
- Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations
Based on the analysis, we recommend the following actions:

Invest in marketing and promotions during peak sales seasons to maximize revenue.
Focus on expanding and promoting products in Category A.
Implement a customer segmentation strategy to target high-LTV customers effectively.


### Limitations
I had to remove all zero values from the budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References
- SQL for Businesses by Werty.
- Stack Overflow
