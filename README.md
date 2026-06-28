# barkhasrivastava_bitsom_ba_2511918-_part3_regression_insights

##### Retail Sales Regression Analysis

###### Business Problem Summary

This project analyzes the factors associated with **monthly sales** across retail stores using linear regression techniques. The objective is to identify which operational and business variables have the strongest relationship with sales performance and provide data-driven recommendations for improving business outcomes.

The analysis supports leadership decisions related to marketing investment, customer traffic, pricing strategy, and store operations.

\---

###### Dataset Description

The dataset contains monthly operational and sales information for multiple retail stores.

The data includes business metrics such as:

* Store ID
* Region
* Store Type
* Marketing Spend
* Customer Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability Percentage
* Competitor Distance
* Customer Rating
* Holiday Flag
* Monthly Sales (Target Variable)

The dataset was cleaned before analysis, while preserving the original data in a separate worksheet.

\---

###### Dependent and Independent Variables

###### Dependent Variable

* **Monthly Sales**

This is the target variable that the regression models aim to predict.

###### Independent Variables

The following variables were evaluated as predictors:

* Marketing Spend
* Footfall
* Average Discount Percentage
* Staff Count
* Inventory Availability Percentage
* Competitor Distance
* Customer Rating
* Holiday Flag
* Region (Dummy Variables)
* Store Type (Dummy Variables)

\---

###### Regression Approach

Three regression models were developed.

###### Model 1: Simple Linear Regression

Dependent Variable:

* Monthly Sales

Independent Variable:

* Marketing Spend

Purpose:

Evaluate the relationship between marketing investment and sales.

\---

###### Model 2: Simple Linear Regression

Dependent Variable:

* Monthly Sales

Independent Variable:

* Footfall

Purpose:

Measure the impact of customer traffic on sales.

\---

###### Model 3: Multiple Linear Regression

Dependent Variable:

* Monthly Sales

Independent Variables:

* Marketing Spend
* Footfall
* Average Discount Percentage
* Region Dummy Variable

Purpose:

Evaluate the combined effect of multiple business factors on monthly sales while controlling for the influence of other variables.

The final model achieved an **R² of approximately 0.7853**, indicating that it explains about **78.53%** of the variation in monthly sales.

\---

###### Dummy Variable Approach

Categorical variables cannot be directly included in a regression model, so dummy variables were created.

Dummy variables were generated for:

* Region

One category was excluded as the **reference category** to avoid the **dummy variable trap (perfect multicollinearity)**.

For example:

|Region|Dummy Variable|
|-|-|
|North|Region\_North = 1|
|Reference Region|Region\_North = 0|

The omitted category serves as the baseline against which the included dummy variable is compared.

\---

###### Model Comparison Summary

|Model|Variables Used|R²|Key Findings|
|-|-|-|-|
|Simple Regression 1|Marketing Spend|Moderate|Marketing spend has a significant positive relationship with monthly sales.|
|Simple Regression 2|Footfall|Higher than Model 1|Footfall is one of the strongest predictors of monthly sales.|
|Multiple Regression|Marketing Spend, Footfall, Average Discount %, Region Dummy|**0.7853**|Best-performing model, explaining approximately 78.53% of the variation in monthly sales.|

###### Significant Variables

* Marketing Spend (Positive)
* Footfall (Positive)
* Average Discount Percentage (Negative)

###### Statistically Weak Variable

* Region Dummy Variable (Not statistically significant)

\---

###### Final Model Selected

The **Multiple Linear Regression Model** was selected as the final model because it:

* Achieved the highest explanatory power (R² ≈ 0.7853).
* Included multiple operational factors simultaneously.
* Controlled for the effects of several predictors.
* Provided the most useful business insights for decision-making.

\---

##### Business Recommendation

Based on the regression analysis, the following recommendations are made:

* Increase investment in marketing activities that generate measurable returns.
* Prioritize initiatives that increase customer footfall through promotions, loyalty programs, and improved customer experience.
* Use discounts selectively rather than relying on broad discounting strategies.
* Investigate stores with large residuals to identify operational strengths and weaknesses.
* Continue improving data collection to support more accurate predictive models.

The analysis indicates that **customer footfall** and **marketing spend** are the strongest drivers associated with monthly sales.

\---

###### Assumptions and Limitations

###### Assumptions

* Relationships between variables are linear.
* Observations are independent.
* Residuals are approximately normally distributed.
* Variance of residuals is constant (homoscedasticity).
* Predictors are not perfectly correlated.

###### Limitations

* Regression identifies statistical associations but does not establish causality.
* External factors such as weather, local economic conditions, customer demographics, and competitor promotions were not included.
* Prediction errors remain for some stores, as shown by the residual analysis.
* Results are based on historical data and may not fully reflect future business conditions.

\---

# Screenshots Included

The project submission includes screenshots of:

* Original Dataset
* Cleaned Dataset
* Dummy Variable Creation
* Simple Regression Output (Marketing Spend)
* Simple Regression Output (Footfall)
* Multiple Regression Output
* Prediction and Residual Calculation
* Model Comparison Table
* Residual Analysis
* Final Recommendation

These screenshots provide evidence of the regression analysis process and support the findings presented in this report.

