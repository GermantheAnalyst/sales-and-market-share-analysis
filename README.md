# Sales-and-Market-share-analysis

Project Title: Sales and Market Share Analysis for VanArsdel Electronics

## Client Background:

VanArsdel is a leading manufacturer known for its high-end electronic products catering to both personal and professional sectors. The company aimed to enhance its understanding of sales performance and market share across three significant markets where it operates. To achieve this goal, VanArsdel recognized the necessity of a thorough analysis that would involve evaluating its performance relative to competitors.

To gain a comprehensive view, VanArsdel collaborated with a third-party marketing firm specializing in market analytics. This partnership was essential for collecting anonymized industry sales data, which would allow VanArsdel to maintain confidentiality while obtaining valuable insights. By benchmarking against this data, the company could identify trends, sales dynamics, and potential areas for improvement.

The role of such an analysis is particularly crucial for a Chief Marketing Officer (CMO), who must constantly evaluate the company’s product performance and competitive standing. The gathered insights would not only highlight how VanArsdel's products fared in comparison to similar offerings from competitors but also provide a clearer understanding of customer preferences and market demands. This strategic approach would enable VanArsdel to make informed decisions, potentially driving product innovation, refining marketing strategies, and enhancing customer engagement in the competitive landscape. 

Ultimately, such a comprehensive analysis is aimed at not just understanding the current market position but also planning for future growth and success in an ever-evolving market.

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


## Key Findings:

Key findings included:

It's clear that VanArsdel is dominating the revenue charts with an impressive £11.3 million, representing about 51% of the total revenue. In stark contrast, Currus is lagging significantly at only £1.2 million.

March proved to be an exceptional month, generating £4.8 million, more than double the £2.1 million earned in January, which turned out to be our lowest month.

There's a notable correlation between sales revenue and the volume of units sold. For instance, when VanArsdel experienced revenue growth in 2016, it was mirrored by an increase in unit sales. Conversely, a decline in their revenue in 2017 resulted in a downfall in unit sales across the board, indicating a robust relationship between these two factors.

March itself contributed nearly 22% of our total revenue during the review period, with fluctuations in monthly revenue showing a range from just above £2 million to almost £5 million.

Comparing the current year's sales to the previous year's figures, VanArsdel observed the most significant decline, with this year's sales exceeding last year's by over £14 million. 

In April, the Maximus UM product gained traction, accounting for about 8% of our total revenue.

Regionally, California stands out as our highest-performing area, generating £28.4 million, which is more than double New York’s revenue of £13.9 million. Texas ranks in between, with £25.7 million, emphasizing that California alone contributes nearly 42% to our overall revenue.

 ## Recommendations:

**Recommendations for VanArsdel:**

1. **Capitalize on March's Success:**
   "March was a clear winner, bringing in significantly more revenue than any other month. Let's dig deeper into what drove those sales. Was it a specific promotion, a new product launch, or seasonal demand? Understanding this will help us replicate that success in future months."

2. **Address the Year-Over-Year Decline:**
   "We saw a big drop in VanArsdel's sales compared to last year. We need to investigate why this happened. Did competitors introduce new products? Were there changes in the market? Let's develop a plan to regain that lost ground."

3. **Focus on the Maximus UM Product:**
   "The Maximus UM product performed exceptionally well in April. Let's analyze why it did so well. Can we replicate that success with other products or in other months?"

4. **Strengthen Currus's Performance:**
   "Currus's sales are significantly lower than VanArsdel's. We need to understand the underlying causes. Are their products less competitive? Is their marketing less effective? Let's develop a strategy to boost their sales."

5. **Leverage California's Market:**
   "California is our strongest market by far. Let's focus on maintaining and expanding our presence there. We could explore targeted marketing campaigns or partnerships to further increase sales."

6. **Analyze Regional Differences:**
   "We see significant differences in sales across regions. Let's analyze the factors that contribute to these differences. Are there differences in consumer preferences or purchasing power? This will help us tailor our strategies to each region."

7. **Monitor the Correlation Between Units and Revenue:**
   "The strong correlation between units sold and revenue is a key insight. Let's continue to monitor this relationship and use it to inform our forecasting and inventory management."

8. **Investigate January's Low Revenue:**
   "January's revenue was significantly lower than other months. Let's investigate the reasons behind this drop and develop strategies to mitigate seasonal fluctuations."


## Conclusion:

The analysis conducted provided VanArsdel with critical insights regarding its sales performance and market share, which are essential metrics for understanding how well the company is performing relative to competitors and market trends. By utilizing Power BI's advanced features, we were able to develop interactive dashboards that provide stakeholders with real-time access to key performance indicators (KPIs) and sales data. 

These dashboards not only present data in a visually appealing manner but also allow users to drill down into specific metrics, analyze trends over time, and identify areas for improvement. The interactivity of the dashboards encourages stakeholders to explore the data themselves, fostering a culture of data-driven decision-making within the organization.

This project serves as a compelling example of how data analytics can significantly influence marketing and sales strategies. By uncovering patterns and correlations within the sales data, VanArsdel can tailor its marketing efforts to better target specific customer segments, optimize pricing strategies, and enhance product offerings. Furthermore, the insights derived from the analysis allow the company to proactively adjust its strategies in response to market changes, ultimately driving growth and maintaining competitive advantage. Overall, this initiative underscores the importance of leveraging data analytics as a vital tool for informing business decisions and optimizing performance.
