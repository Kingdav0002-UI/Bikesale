# Bikesale
Bikesale dataset project built with just Excel

# Introduction

This project analyzes a bike sales dataset containing customer demographic and socioeconomic information to identify the factors that influence bike purchasing behavior. The objective is to uncover patterns among customers and provide insights that can help businesses improve their marketing strategies, customer targeting, and sales performance.

# Data Description

- **Dataset Name:** Bike Sales Dataset
- **Number of Records:** 1,000 customers
- **Number of Features:** 14 columns

### Variables Included

| Variable | Description |
|----------|-------------|
| ID | Unique customer identifier |
| Marital Status | Customer's marital status |
| Gender | Male or Female |
| Income | Annual income |
| Children | Number of children |
| Education | Highest education level |
| Occupation | Customer occupation |
| Home Owner | Home ownership status |
| Cars | Number of cars owned |
| Commute Distance | Distance travelled to work |
| Region | Customer's geographical region |
| Age | Customer age |
| Age Bracket | Age category |
| Purchased Bike | Target variable indicating whether a customer purchased a bike (Yes/No) |

# Methodology

The analysis followed a structured data analysis process:

1. Loaded and explored the dataset.
2. Examined the dataset structure and variable types.
3. Performed descriptive statistical analysis.
4. Analyzed customer demographics.
5. Compared customer characteristics against bike purchasing decisions.
6. Identified trends, patterns, and relationships.


# Analysis and Findings

## Dataset Overview

- Total Customers: **1,000**
- Customers who purchased bikes: **481 (48.1%)**
- Customers who did not purchase bikes: **519 (51.9%)**

The dataset is relatively balanced, making it suitable for descriptive analysis and predictive modeling.

### Gender Analysis

- Male customers:
  - Purchased: 242
  - Not Purchased: 269

- Female customers:
  - Purchased: 239
  - Not Purchased: 250

**Finding:** Bike purchases are almost evenly distributed across both genders, suggesting gender has minimal influence on purchasing decisions.

### Marital Status Analysis

- Married Customers
  - Purchased: 231
  - Not Purchased: 307

- Single Customers
  - Purchased: 250
  - Not Purchased: 212

**Finding:** Single customers are more likely to purchase bikes than married customers.

### Regional Analysis

| Region | Purchased | Not Purchased |
|---------|-----------|---------------|
| North America | 220 | 288 |
| Europe | 148 | 152 |
| Pacific | 113 | 79 |

**Finding:**

- The Pacific region has the highest purchase rate relative to its customer base.
- North America has the largest customer population but also the highest number of non-buyers.

### Education Analysis

Customers with:

- Bachelor's Degrees recorded the highest number of purchases.
- Graduate Degrees also showed relatively strong purchase behavior.
- Partial High School education had the lowest purchase rate.

**Finding:** Higher education appears to be associated with a greater likelihood of purchasing a bike.


# Insights

Based on the analysis, several important business insights emerged:

- Nearly half of all customers purchased a bike, indicating healthy market demand.
- Gender is not a significant differentiator in bike purchasing behavior.
- Single customers demonstrate a higher tendency to purchase bikes than married customers.
- Customers from the Pacific region exhibit the strongest purchasing behavior.
- Individuals with Bachelor's and Graduate Degrees are more likely to purchase bikes.
- Education level appears to positively influence purchasing decisions.


# Recommendations

Based on the findings, the following recommendations are suggested:

1. Focus marketing campaigns on single adults, who show a higher likelihood of purchasing bikes.

2. Increase promotional efforts in the Pacific region, where customer conversion rates are strongest.

3. Develop targeted campaigns for educated professionals, particularly customers with Bachelor's and Graduate Degrees.

4. Create personalized offers based on customer demographics such as age, income, occupation, and commute distance.

5. Investigate why many North American customers do not purchase bikes despite representing the largest customer segment.


# Conclusion

The Bike Sales dataset provides valuable insights into customer purchasing behavior. While gender has little impact on buying decisions, factors such as marital status, education level, and geographic region appear to play a more significant role. Customers who are single, highly educated, and located in the Pacific region demonstrate higher purchase rates.

These findings can help businesses improve customer targeting, optimize marketing campaigns, and increase sales through data-driven decision-making. Future analyses could incorporate predictive analytics and customer segmentation techniques to further enhance business performance.
