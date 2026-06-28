##### Model Equations

###### Overview

To identify the factors associated with monthly sales, two simple linear regression models and one multiple linear regression model were developed. The simple regression models evaluated the impact of individual predictors, while the multiple regression model assessed the combined influence of several business variables.

\---

###### Model 1: Simple Linear Regression (Marketing Spend)

###### Regression Equation

\[
{Monthly Sales} = 560777.35 + 2.1296(Marketing Spend)
]

###### Coefficient Explanation

**Intercept (560,777.35)**

The intercept represents the estimated monthly sales when marketing spend is zero. Although a store is unlikely to spend nothing on marketing, the intercept serves as the starting point for the prediction equation.

**Marketing Spend Coefficient (2.1296)**

For every additional one-unit increase in marketing spend, monthly sales are expected to increase by approximately **2.13 units**, assuming all other factors remain unchanged.

###### Business Interpretation

The model indicates a strong positive relationship between marketing investment and monthly sales. Increasing marketing expenditure is associated with higher sales, making marketing an important business driver.

\---

###### Model 2: Simple Linear Regression (Footfall)

###### Regression Equation

\[
{Monthly Sales} = 446410.5829 + 35.68(Footfall)
]

###### Coefficient Explanation

**Intercept**

Represents the estimated monthly sales when customer footfall is zero, i.e., 446410.5829 

**Footfall Coefficient**

Indicates how much monthly sales are expected to increase for each additional customer visiting the store.

###### Business Interpretation

The model demonstrates that stores attracting more customers generally achieve higher monthly sales. Customer traffic is therefore one of the strongest operational drivers of business performance.

\---

###### Model 3: Multiple Linear Regression (Final Model)

###### Regression Equation

\[
{Monthly Sales} =407920.82 +1382.18(Region North) +1.1274(Marketing Spend) +33.5179(Footfall) -89140.45(Average Discount %)
]

\---

###### Explanation of Each Coefficient

###### Intercept (407,920.82)

The intercept represents the estimated monthly sales for a store in the reference region when all numerical predictor values are zero. Although this situation is unlikely in practice, it provides the baseline value for the regression model.

\---

###### Marketing Spend (Coefficient = 1.1274)

Holding all other variables constant, each additional unit of marketing spend is associated with an increase of approximately **1.13 units** in monthly sales.

**Business Meaning**

Marketing investment contributes positively to sales performance, supporting continued investment in effective marketing campaigns.

\---

###### Footfall (Coefficient = 33.5179)

Each additional customer visiting the store is associated with an increase of approximately **33.5 units** in monthly sales, assuming the other variables remain unchanged.

**Business Meaning**

Customer traffic has the strongest positive association with sales and should be a key operational focus.

\---

###### Average Discount Percentage (Coefficient = −89,140.45)

An increase in the average discount percentage is associated with a decrease in monthly sales after accounting for the effects of the other variables.

**Business Meaning**

Heavy discounting does not necessarily lead to higher sales. Instead, discounts should be used strategically to support revenue while protecting profitability.

\---

###### Region North Dummy Variable (Coefficient = 1,382.18)

This coefficient compares stores in the North region with the reference region.

A positive coefficient suggests slightly higher sales for North-region stores after controlling for the other predictors. However, the variable was not statistically significant, indicating that regional differences alone do not meaningfully explain sales variation in this model.

\---

###### Dummy Variable Explanation

The variable **Region** is categorical and therefore cannot be entered directly into a regression model.

To include it, dummy variables were created.

For example:

|Region|Region\_North|
|-|-|
|North|1|
|Reference Region|0|

Only one dummy variable was included to avoid the **dummy variable trap**, which occurs when all categories are included simultaneously and creates perfect multicollinearity.

\---

###### Reference Category Used

The omitted region served as the **reference category**.

All coefficient estimates for the dummy variable represent differences in monthly sales relative to this reference region.

\---

###### Final Model Selected

The **Multiple Linear Regression Model** was selected as the final model.

\---

###### Reason for Selecting the Final Model

The multiple regression model was selected because it provides the most comprehensive understanding of the factors associated with monthly sales.

Compared with the simple regression models, it:

* Explains a larger proportion of the variation in monthly sales (**R² ≈ 0.7853**).
* Evaluates several business drivers simultaneously.
* Measures the independent effect of each predictor while controlling for the influence of the others.
* Produces more reliable insights for strategic decision-making.

From a business perspective, the model demonstrates that customer footfall and marketing spend are the strongest positive drivers of monthly sales, while higher discount levels are associated with lower sales after accounting for other variables. These findings provide a stronger basis for decisions related to marketing investment, customer acquisition, and pricing strategy than any single-variable model.

