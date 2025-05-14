# Housingdata-analysis

# 1. Introduction
This report presents a comprehensive data analysis of a housing dataset containing information on residential properties. The goal of the analysis is to uncover key patterns that influence house prices based on the amenities in the different houses in the areas. Also to assess data quality, and build predictive insights to inform pricing strategies or investment decisions.

# 2. Objective
The purpose of this project is to analyze a housing dataset to:
● Determine the average, minimum, and maximum house prices in the different
Area
● Identify structural and feature-based patterns influencing pricing
● Explore the relationship between property area, air-condition, number of bedrooms,
and house pricing
 Target Variable (Sales Price)
● Support predictive insights and guide prescriptive strategies for pricing and development focus

# 3. Project Overview

This project involved analyzing a dataset with 378 housing records across 13 variables using Microsoft Excel. The variables include 6 numerical features (i.e: price, area, bedrooms, bathrooms, stories and number of parking) and 7 categorical features (e.g., basement, air conditioning, furnishing status, main road, guest room, hot water heating, and preferred area). We performed descriptive, diagnostic, predictive, and prescriptive analytics using Excel techniques such as PivotTables, formulas, charts, correlation, and regression

# 4. Methodology

A. Data Cleaning
● Column Adjustments: Used auto-fit for better visibility (manual and VBA method).
● Filter Application: Enabled filters to inspect specific features like main road or guestroom (none found).
● Duplicates: No duplicate records found.
● Blank Cells: Checked using filters and 'Go To Special' function; none f● Priceound.
● Formatting: Bolded headers and froze the top row. Structured the dataset as a table for analysis readiness.

B. Exploratory Data Analysis (EDA)

![image](https://github.com/user-attachments/assets/cf3d3210-386f-47c5-9298-7bed3edb98b7)


● Price:
○ Max: GHS 13,300,000.00
○ Min: GHS 1,750,000.00
○ Average: GHS 4,767,740.19
○ Total Income: GHS 1,802,205,790.00

● Area:
○ Max: 16,200 sq ft
○ Min: 1,700 sq ft
○ Average: 5,264 sq ft

● Bedrooms:
○ Max: 6 | Min: 1 | Average: 3

● Other Features:
○ Bathrooms, Stories, Parking all range from 1–4 with averages of 1–2 units

# ii. Categorical Summary (PivotTable Counts)


# iii. Price Ranges
● Low Price: 254 homes
● Medium Price: 100 homes
● High Price: 24 homes

# 5. Data Visualization – Dashboard 1
![image](https://github.com/user-attachments/assets/a286a88e-e9e5-43eb-a31f-d057f16fa45a)

# Visuals Included:

● Bar chart of Price Range

● Scatter Plot: Area vs Price (with trendline & R² = 0.2691)

● Bar chart: Air Conditioning Status across Price Ranges

● KPIs: Max Area, Low Price House Count, Air-conditioned Homes

# Story:
The majority of homes (67%) fall into the low-price category. Despite the highest area being 16,200 sq ft, many large-area houses remain in lower price brackets. Air conditioning is present in 115 homes, most of which are medium-to-high priced. There is a weak positive correlation between area and price (R² = 0.2691), suggesting that area alone is not the dominant driver of price.

# 6. Data Analysis
# Correlation Analysis

![image](https://github.com/user-attachments/assets/0083531b-e39b-45c7-a022-95a2a3a6a67d)

![image](https://github.com/user-attachments/assets/cffd8eb1-aa98-477e-b5f3-ec626d96dcb8)

# ● Price vs Area: Weak positive correlation (r ≈ 0.52)
● Price vs Bedrooms: Mild relationship

● Interpretation: Area influences price more than number of bedrooms but is not a sole factor.

# Price Categories using IF Logic

Used Excel IF statements to classify homes:

○ Low: < GHS 5,000,000

○ Medium: 3M–8M

○ High: > 8M

Used PivotTables to explore how features like AC, preferred area, and furnishing status vary across price bands.

# 7. Dashboard 2 – Deep Insights & Predictive Analysis

![image](https://github.com/user-attachments/assets/cf80aa13-6a58-462e-8532-e615198a14dc)

# Visuals Included:

● Pie charts: AC and Prefarea status

● Column charts: Furnishing distribution

● Regression trendline chart: Area vs Price

# Story:
Higher-priced homes tend to have air conditioning, be in preferred areas, and be furnished. Regression analysis shows an R² of 0.2691, indicating a weak model fit but still helpful in predicting general trends.

# 8. Results – Full Data Story

The dataset reveals that the majority of houses are priced below GHS 5 million. Factors such as AC, preferred area, and furnishing increase the likelihood of higher pricing. However, area alone does not strongly dictate price. The average home has 3 bedrooms, 1 bathroom, and minimal luxury features.

Predictive modeling indicates that price trends are not affected by area; other factors significantly influence final pricing. The most valuable homes tend to be fully equipped and well-located


# 9. Discussion & Conclusion
# Insights:
● Developers should invest in comfort features (AC, furnishing) and location selection (preferred areas) for value addition.

● The majority of homes are underpriced due to a lack of features.

● Regression is useful, but should be supported by feature scoring or advanced modeling for stronger predictions.

# 10.   Recommendations:

● Add a guestroom and improve heating systems to increase value
•	The strongest predictors of housing price are related to size, quality and play grounds, markets should be considered in future developments
● Target developments with more premium features for preferred area properties

● Use What-If Analysis for development planning (e.g., how much area to achieve the target price)


# Prepared By: Nicholas Tawiah

# Toolkits Used: Excel (Formulas, PivotTables, Charts, Regression)

# Project Dataset: Housing Dataset (.xlsm)



# End of Report




