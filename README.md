# Sales-and-Market-share-analysis

Project Title: Sales and Market Share Analysis for VanArsdel Electronics

## Client Background:

VanArsdel, a manufacturer of high-end electronic products for both personal and professional use, sought to understand its sales performance and market share in three key markets. To benchmark against competitors, VanArsdel partnered with a third-party marketing firm to gather anonymized industry sales data. This analysis, typical for a Chief Marketing Officer (CMO), aimed to provide insights into both internal product performance and external competitive positioning.

## Problem Statement:

The primary objective of this project was to analyze VanArsdel's sales data alongside industry market data to:
- Determine VanArsdel's market share in each target market.
- Identify top-performing products and regions.
- Uncover trends in sales and market share over time.
- Provide actionable insights to inform marketing and sales strategies."

## Data Sources and Preparation:

The data for this analysis was provided in an Excel workbook containing:
VanArsdel's sales data (product, date, geography, sales figures).
Anonymized industry sales data.
Product and geographical dimension tables.
Data preparation involved:
1. Importing data into Power BI Desktop. ![Screenshot 2025-03-04 202807](https://github.com/user-attachments/assets/5a3aa4e5-e45a-449b-b513-d2f3fcc57473)

2. Cleaning and transforming data to ensure consistency and accuracy (e.g., handling missing values, standardizing date formats). <img width="1199" alt="image" src="https://github.com/user-attachments/assets/010bb92b-fe52-44fa-bd14-29d25c192b8a" />

3. Creating relationships between tables to build a robust data model. ![Screenshot 2025-03-04 203652 m](https://github.com/user-attachments/assets/70e037eb-45bc-47c7-8890-aae6c5afb301)

   


## Analytical Techniques and Methodology:

The analysis was conducted using Power BI Desktop and Power BI Service. Key techniques included:
Calculating market share using DAX measures.
Creating time series charts to visualize sales and market share trends, also group other competitors and analysing their strength agaijnst vanarsdel.
Developing interactive dashboards to explore product and regional performance (see below).
Utilizing Power Query for data transformation and loading (ETL). Which serves as the kitchen of Power BI, where data cleaning and transformation takes place by using m-language
Data model which helps in reducing data redundancies and also creating relationships between the key fact tables and the dimension table to enable ease of cardinality among the tables. Since the datasset contains 4 table the rule of thumbs states that there should be atleast 3 relationships.
DAX functions and expression (DAX). Data analysis expression for cretaing explicit aggregage, measures, calculated columns and functions to analyze KPI's and also expressions which helps in creating total revenue, YoY revenues, conditional coulmn e.t.c ![Screenshot 2025-03-04 211551 dax](https://github.com/user-attachments/assets/bad4676d-9320-4c85-9459-7a015af925e4)

The document was structured and presents a screenshots of the dashboard that shows the analysis for the year 2017. This was designed to be easily followed by the stakeholdes and end user for clearification of the analysis.<img width="1064" alt="image" src="https://github.com/user-attachments/assets/0ec1d1b9-39ca-4ed0-98d6-d71eeab5be20" />


## Key Findings and Visualizations:

Key findings included:
Specific finding 1, e.g., "VanArsdel's market share in the [Region] market was [Percentage], indicating a [Trend] over the past year.
[Specific finding 2, e.g., "The [Product] line demonstrated the highest sales growth, particularly in the [Region] market."]
[Specific finding 3, e.g., "Seasonal trends were observed in sales, with peak sales occurring during [Month(s)]."]
"Visualizations included:
Market share pie charts by region.
Time series line charts showing sales and market share trends.
Bar charts comparing product sales across regions.
Interactive dashboards allowing users to drill down into specific data points.
Include screenshots of key visualizations with clear titles and labels.

 ## Business Implications and Recommendations:

Based on the analysis, the following recommendations were made:
[Recommendation 1, e.g., "Increase marketing efforts in the [Region] market to capitalize on growth opportunities."]
[Recommendation 2, e.g., "Invest in product development for the [Product] line to maintain its competitive advantage."]
[Recommendation 3, e.g., "Optimize inventory management to align with seasonal demand fluctuations."]
These recommendations aimed to improve VanArsdel's market share, increase sales revenue, and enhance overall business performance.
If applicable, include the outcome of the recommendations.


## Conclusion:

This analysis provided VanArsdel with valuable insights into its sales performance and market share. By leveraging Power BI's capabilities, we were able to create interactive dashboards that empower stakeholders to make data-driven decisions. This project demonstrates the power of data analytics in informing marketing and sales strategies.
