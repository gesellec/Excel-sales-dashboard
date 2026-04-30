# Sales Analysis Summary

## Overview
For my project, I utilized Excel to evaluate revenue patterns and identify statistically significant drivers of net sales for the Pelican stores. The analysis combines exploratory data analysis (EDA) and regression modeling to examine relationships between customer characteristics and spending behavior.

## Exploratory Data Analysis

The data shows strong variation in purchasing behavior across customer groups. Female customers purchased 10,674 items, compared to 4,890 items purchased by males. This represents approximately 68.6% of total purchases, indicating a heavily skewed distribution toward female consumers.

Marital status is relatively balanced, with 723 married customers and 656 single customers. However, married customers exhibit slightly higher spending behavior, suggesting a marginally greater contribution to total net sales.

Customer age ranges from approximately 25.5 to 90 years, with a mean of 54.03. This indicates that the customer base is centered around a middle-aged demographic.

Transaction-level analysis shows that 1,089 out of 1,388 purchases were non-promotional, representing approximately 78.5% of total transactions. Promotional purchases account for only 21.5%, indicating that the majority of revenue is generated without promotional incentives.

The conditional distribution of promotional purchases shows that females account for 227 of the 299 promotional transactions, compared to 72 for males. This suggests that promotional responsiveness differs across customer segments.

Most transactions involve between 4 and 10 items, indicating a consistent purchasing pattern.

## Regression Analysis

Both simple linear regression and multiple linear regression models were conducted to evaluate the relationship between customer characteristics and net sales.

In the multiple regression model, net sales is the dependent variable, while age and customer income are independent variables.

The overall model is statistically significant, as indicated by the F-statistic p-value (Significance F ≈ 2.17e-05).

However, the model has a low R-squared value (R² ≈ 0.0159), meaning only about 1.59% of the variation in net sales is explained by the model.

Customer income has a positive coefficient (β ≈ 0.115) and is highly statistically significant (p-value ≈ 0.00011). Since the p-value is lower than .05, this indicates that higher-income customers tend to spend more.

Age has a positive coefficient (β ≈ 2.96) and is statistically significant (p-value ≈ 0.0135). This suggests that older customers tend to generate higher revenue.

Education-related variables also show positive and statistically significant relationships with net sales, with p-values approximately 0.005 and 0.0028.

Distance has a negative coefficient,meaning that as distance increases, net sales decrease.

The intercept is not statistically significant.

We can conclude that while there are some statistically significant predictors, the low R-squared indicates that additional variables are needed to better explain customer behavior for a better fit. 

## Business Implications

Sales are primarily driven by female customers and higher-income individuals. These groups represent key segments for targeted marketing strategies.

The strong positive relationship between income and spending suggests that high-income customers has a high impact on revenue.

Promotions are underutilized, accounting for only 21.5% of transactions. Targeted promotional strategies could improve effectiveness.

The negative relationship between distance and sales highlights the importance of accessibility.

## Conclusion

This project demonstrates how exploratory data analysis and regression modeling can be used to evaluate sales performance.

While income and age are statistically significant predictors, the low R-squared value indicates that customer behavior is influenced by multiple additional factors.

Overall, the analysis highlights the importance of combining descriptive and statistical methods to generate meaningful business insights.
