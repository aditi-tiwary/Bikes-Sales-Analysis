# Bike Sales Analysis

## Table of Contents

- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Recommendations](#recommendations)

### Project Overview
---

This data analysis project aims to provide insights into the sales performance of bikes. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of different factors considered by the customers before purchasing a bike.


### Data Sources

Sales Data: The primary dataset used for this analysis is the "bike sales raw data.xlsx" file, containing detailed information about each bike sale.

### Tools

- Excel - Data Cleaning, Data Analysis through Pivot Tables, Creating Dashboard

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
1. Data loading and inspection- Removed 26 duplicate entries from the raw dataset.
2. Data cleaning- Replaced 'M' to 'Married' and 'S' to 'Single' in 'Marital Status' column. Likewise, replaced 'M' to 'Male' and 'F' to 'Female' in 'Gender' column for more clarity.
3. Data formatting- Set the 'Income' column as Currency type and removed the decimals.
4. Created a new column 'Age Brackets' to categorize age groups into 'Adolscent','Middle Age','Old' using IF function.
5. Value Modification- Replaced '10+ Miles' in the 'Commute Distance' column to 'More than 10 Miles' for better data interpretation.

### Exploratory Data Analysis

EDA involved exploring the sales data to answer key questions, such as:

- Is the average income of both male and female who purchased the bike higher than those who did not?
- How is the bike purchase affected by the commute distance?
- Which age group purchased more bikes?

### Data Analysis and Visualization

1. Average Income of Male and Female who purchased bike or not
   
    ![Screenshot 2024-06-29 131631](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/5baef732-ac7b-45bc-af39-25a553fd608f)

   

   



### Results/Findings

The analysis results are summarized as follows:
1. The company's sales have been steadily increasing over the past year, with a noticeable peak during the holiday season.
2. Product Category A is the best-performing category in terms of sales and revenue.
3. Customer segments with high lifetime value (LTV) should be targeted for marketing efforts.

### Recommendations

Based on the analysis, we recommend the following actions:
- Invest in marketing and promotions during peak sales seasons to maximize revenue.
- Focus on expanding and promoting products in Category A.
- Implement a customer segmentation strategy to target high-LTV customers effectively.

### Limitations

I had to remove all zero values from budget and revenue columns because they would have affected the accuracy of my conclusions from the analysis. There are still a few outliers even after the omissions but even then we can still see that there is a positive correlation between both budget and number of votes with revenue.

### References

1. SQL for Businesses by werty.
2. [Stack Overflow](https://stack.com)

😄

💻

|Heading1|Heading2|
|--------|--------|
|Content|Content2|
|Python|SQL|

`column_1`

**bold**

*italic*
