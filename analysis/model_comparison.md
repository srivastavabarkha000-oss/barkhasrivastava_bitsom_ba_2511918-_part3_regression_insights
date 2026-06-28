##### Model Comparison

###### Overview

Three regression models were developed to identify the factors associated with **monthly sales** across retail stores. Two simple linear regression models evaluated the impact of individual predictors, while a multiple regression model examined the combined effect of several business variables.

\---

###### Model Comparison Summary

|Model|Dependent Variable|Independent Variable(s)|R²|Significant Variables|Business Usefulness|
|-|-|-|-|-|-|
|**Model 1: Marketing Spend Regression**|Monthly Sales|Marketing Spend|Moderate|Marketing Spend (p < 0.05)|Demonstrates that increasing marketing investment is associated with higher sales. Useful for evaluating marketing ROI.|
|**Model 2: Footfall Regression**|Monthly Sales|Footfall|High|Footfall (p < 0.05)|Shows that customer traffic is a strong predictor of sales performance. Useful for store operations and customer acquisition strategies.|
|**Model 3: Multiple Regression**|Monthly Sales|Marketing Spend, Footfall, Average Discount %, Region North Dummy|**0.7853**|Marketing Spend, Footfall, Average Discount %|Provides the most comprehensive understanding of sales drivers by evaluating multiple factors simultaneously. Supports strategic business decision-making.|

\---

###### Comparison of Explanatory Power (R²)

###### Model 1 – Marketing Spend

* Explains a moderate proportion of the variation in monthly sales.
* Marketing investment has a statistically significant positive effect on sales.
* Useful for understanding the impact of promotional spending but does not account for other important business factors.

###### Model 2 – Footfall

* Produces a higher R² than the marketing-only model.
* Customer traffic explains a larger share of sales variation.
* Indicates that increasing store visits is one of the strongest drivers of revenue.

###### Model 3 – Multiple Regression

* **R² = 0.7853**
* Explains approximately **78.53%** of the variation in monthly sales.
* Provides the strongest predictive performance because it considers multiple business variables simultaneously.

\---

###### Significant Variables

###### Marketing Spend

* Positive coefficient
* Statistically significant (p < 0.05)
* Higher marketing expenditure is associated with increased monthly sales.

###### Footfall

* Positive coefficient
* Highly statistically significant (p < 0.05)
* The strongest predictor of monthly sales in the model.

###### Average Discount %

* Negative coefficient
* Statistically significant (p < 0.05)
* Higher discount percentages are associated with lower monthly sales after controlling for other variables.

###### Region North Dummy

* Not statistically significant (p > 0.05)
* Regional location does not appear to meaningfully influence sales after accounting for the other predictors.

\---

###### Business Usefulness

###### Model 1

Useful for evaluating the effectiveness of marketing expenditure. It supports budgeting decisions but ignores other important operational factors that influence sales.

###### Model 2

Provides valuable insight into the relationship between customer traffic and sales performance. It can guide initiatives aimed at increasing store visits through promotions, advertising, and improved customer experience.

###### Model 3

The multiple regression model offers the most complete and reliable business insights. It allows management to assess the independent contribution of several variables simultaneously while controlling for the effects of the others. The model supports decisions related to marketing investment, inventory planning, pricing strategy, and operational improvements.

\---

###### Limitations

Although the multiple regression model explains a large proportion of sales variation, several limitations should be considered:

* Regression identifies associations rather than causal relationships.
* External factors such as economic conditions, competitor promotions, weather, and local events are not included.
* Customer demographics and product assortment were not available for analysis.
* The model assumes linear relationships between predictors and sales.
* Results may change if additional variables or future data are incorporated.
* Some predictors may exhibit multicollinearity, which can affect coefficient estimates.

\---

###### Final Recommendation

Among the models evaluated, the **multiple regression model** is the preferred model for business decision-making because it explains the greatest proportion of variation in monthly sales and identifies the most influential drivers of performance.

The analysis suggests that management should:

* Increase marketing investment where return on investment is positive.
* Prioritize initiatives that increase customer footfall.
* Maintain high inventory availability to avoid lost sales.
* Apply discount strategies selectively rather than broadly.
* Avoid making strategic decisions based solely on regional differences, as the regional dummy variable was not statistically significant in this model.

Overall, the multiple regression model provides the strongest analytical foundation for improving monthly sales performance across retail stores.

