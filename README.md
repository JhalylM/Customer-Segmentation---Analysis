# Mall Customer Segmentation & Analysis

## Tags
**Project Type**: Data Science, Machine Learning, Customer Segmentation  
**Tools/Libraries Used**: Python, Pandas, Seaborn, Matplotlib, Plotly, KMeans, Scikit-learn

## Overview

As a data scientist, I was given a dataset containing customer information from a mall, which includes attributes such as customer demographics (Age, Gender), Annual Income, and Spending Score (a behavior-based metric assigned by the mall). The purpose of this dataset is to provide insights into customer behavior and demographics in order to help the marketing department create more effective and targeted campaigns.

The goal of this project is to identify distinct customer segments that exhibit similar behaviors and characteristics. By grouping customers based on these traits, I can provide valuable insights into how different groups of customers behave, how much they spend, and how their demographic factors influence their purchasing patterns.

### Business Impact:
The impact of this project on the business is significant. By segmenting customers into meaningful clusters, the marketing team can:
- Tailor promotions and advertising campaigns specifically to each customer group. 
- Optimize marketing efforts by targeting the highest potential segments, such as high-income, high-spending customers.
- Improve customer retention by personalizing communication and offering relevant products and services.
- Streamline advertising budgets, ensuring resources are allocated effectively to the most profitable customer groups.

Ultimately, this project aims to provide the business with a clear understanding of its customer base, leading to improved customer engagement, increased sales, and better overall business outcomes.

## Data Description
The dataset contains 200 records with 5 attributes:
- **CustomerID**: Unique identifier for each customer.
- **Gender**: Gender of the customer (Male/Female).
- **Age**: Age of the customer.
- **Annual Income (k$)**: The annual income in thousands of dollars.
- **Spending Score (1-100)**: A score assigned by the mall indicating the customer’s spending behavior.

### Data Summary:
- **Number of records**: 200
- **Number of features**: 5
- **Missing values**: None
- **Descriptive Statistics**: 
  - Average age: 38.85 years
  - Average annual income: $60.56k
  - Average spending score: 50.20

## Objective Summary
The main objective of this analysis was to segment the customer base into distinct clusters to aid in targeted marketing strategies. The segmentation was based on the relationship between customer features like age, income, and spending score. Various clustering models were applied to the dataset, with the goal of identifying patterns that could be useful for marketing teams in developing specific strategies for different customer segments.

## Key Insights Gained
- **Gender Distribution**: The dataset contains both male and female customers in roughly equal proportions.
- **Customer Behavior**: A significant portion of customers falls within the average spending score, with varying income levels.
- **Age vs Income/Spending**: Customers with higher incomes tend to have higher spending scores, and age did not show as strong a correlation with spending behavior.
- **Segmentation Patterns**: The most effective clusters were formed using only **Annual Income** and **Spending Score**. 
  - Five distinct clusters were identified: 
    1. Low Income/Low Spending
    2. Low Income/High Spending
    3. Medium Income/Medium Spending
    4. High Income/Low Spending
    5. High Income/High Spending

## Conclusion and Recommendations
### Conclusion:
This analysis demonstrated the power of customer segmentation to inform targeted marketing strategies. The most effective segmentation model used only **Annual Income** and **Spending Score**, achieving the highest silhouette score, and identified five distinct clusters of customers based on their spending behavior and income level. Although **Age** was initially considered, it did not significantly contribute to improving the clustering model, suggesting that income and spending habits are the primary drivers of customer behavior.

### Recommendations:
1. **Targeted Promotions**: 
   - **Low Income/High Spending**: Focus on loyalty programs, discounts, and rewards to keep these customers engaged.
   - **High Income/High Spending**: Consider premium offerings, exclusive products, or services to cater to their buying power.
   - **Medium Income/Medium Spending**: Use data-driven campaigns to increase engagement and encourage higher spending.
2. **Data-Driven Campaigns**: Optimize advertising budgets to target the most profitable clusters, such as the **High Income/High Spending** group.
3. **Further Research**: Explore additional features, such as purchasing frequency or product preferences, to refine segmentation models and uncover deeper insights.
4. **Customer Retention**: Build personalized strategies for each segment to improve customer retention and increase the lifetime value of each group.


This project underscores the importance of data-driven decision-making in understanding customer behavior and crafting effective marketing strategies.

