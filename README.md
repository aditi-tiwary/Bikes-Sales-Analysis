# Bike Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Cleaning](#data-cleaning)
- [Results](#results)

### Project Overview
---
This data analysis project aims to provide insights into the sales performance of bikes. By analyzing various aspects of the sales data, we seek to identify trends, make data-driven recommendations, and gain a deeper understanding of different factors considered by the customers before purchasing a bike.

  ![Dashboard gif](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/adba5d11-7b45-4241-b13c-7abd773c196f)

  ![Dashboard](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/b64763cb-d383-4d99-89d9-7c0719f34ccf)

 
### Data Sources
Sales Data: The primary dataset used for this analysis is the "bike sales raw data.xlsx" file, containing detailed information about each bike sale.


### Tools
- **Excel** - Data Cleaning, Data Analysis through Pivot Tables, Data Visualization through Charts, Creating Dashboard.


### Data Cleaning
In the initial data preparation phase, we performed the following tasks:
1. **Data loading and inspection-** Removed 26 duplicate entries from the raw dataset.
2. **Data cleaning-** Replaced 'M' to 'Married' and 'S' to 'Single' in 'Marital Status' column. Likewise, replaced 'M' to 'Male' and 'F' to 'Female' in 'Gender' column for more clarity.
3. **Data formatting-** Set the 'Income' column as Currency type and removed the decimals.
4. **Created a new column** 'Age Brackets' to categorize age groups into 'Adolscent','Middle Age','Old' using IF function.
5. **Value Modification-** Replaced '10+ Miles' in the 'Commute Distance' column to 'More than 10 Miles' for better data interpretation.


### Exploratory Data Analysis
EDA involved exploring the sales data to answer key questions, such as:

- Which gender purchased more bikes respective to their average income?
- How is the bike purchase affected by the commute distance?
- Which age group purchased more bikes?
- Does marital status affect bike sales?
- Which region has more bike sales than others?


### Data Analysis and Visualization

1. **Average income of male and female who purchased the bike or not**
   
    ![Screenshot 2024-06-29 131631](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/5baef732-ac7b-45bc-af39-25a553fd608f)

   ![Gender   Income Chart](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/acec54b1-056e-4589-b46b-671aedfc5edf)


2. **Purchase of bike on the basis of customer's commute**

   ![Commute Distance   Purchase table](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/b30fbea7-33e0-4520-b68c-0b9693c851a6)

   ![Commute Distance   Purchase Chart](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/4bb5bc02-824e-4b93-93a1-0f8c934fc356)


3. **Purchase of bike on the basis of age bracket**

   ![Age Group   Purchase table](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/d7b5ac34-54a4-44e5-9f12-926aa95779e7)

   ![Age group   purchase chart](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/b06a4822-8b34-46bc-845e-484d1c0342c1)


4. **Purchase of Bike on the basis of marital status**

   ![Purchase by Marital Status](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/1adc057e-c724-471a-91ed-a110f308d947)


5. **Purchase of bike on the basis of region**

   ![Purchase by region](https://github.com/aditi-tiwary/Bikes-Sales-Analysis/assets/149948622/3fd40a09-1f75-4950-9446-f98811d67b17)


### Results
The analysis results are summarized as follows:
1. Out of male and female customers, male customers with higher average income purchased more bikes than female customers with lower average income.
2. Shorter commute distances correlate with higher bike purchase.
3. Middle aged customers between 31-54 years are key purchasers, while there is a decline of bike purchase in the old aged customers i.e. above 55 years.
4. Single customers have purchased approximately 4% more bikes than married customers.
5. North America has more customers compared to Pacific and Europe region.


### Recommendations
Based on the analysis, I would recommend the following actions:
- Target group should be male customers with higher income.
- Concentrate on areas with shorter commutes. Meanwhile, diversify products and collaborate to target the issue of longer commutes. 
- Focus on expanding the products in North America as a priority. Meanwhile, launch strategic marketing ideas for other regions to increase the sales.
- Gather youth feedback to increase sales amongst the single customers.Also implement a family-oriented marketing strategies to target married customers effectively.
