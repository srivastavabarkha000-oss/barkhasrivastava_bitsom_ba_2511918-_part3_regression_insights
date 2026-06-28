##### Residual Analysis

###### Objective

Residual analysis was conducted to evaluate the predictive performance of the final multiple regression model.

Residuals were calculated using:

**Residual = Actual Monthly Sales − Predicted Monthly Sales**

* **Positive residual:** Actual sales are greater than predicted (the model under-predicts).
* **Negative residual:** Actual sales are less than predicted (the model over-predicts).

\---

###### Predicted Sales and Residual Calculation

The predicted monthly sales were calculated using the final multiple regression equation. Residuals were then computed by subtracting the predicted sales from the actual monthly sales for each store-month observation.

\---

###### Five Largest Positive Residuals (Under-Predicted Stores)

|Rank|Record (Row)|Predicted Sales|Residual|
|-|-:|-:|-:|
|1|112|598,503.22|**115,107.94**|
|2|104|518,079.69|**107,434.35**|
|3|298|659,230.93|**103,931.52**|
|4|125|814,791.05|**99,753.12**|
|5|254|702,806.55|**96,240.39**|

###### Business Interpretation

These stores achieved substantially higher sales than the model predicted. Possible explanations include:

* Highly effective local marketing campaigns.
* Exceptional store management.
* Strong customer loyalty.
* Temporary local events increasing demand.
* Popular product assortment not captured in the model.
* Other operational advantages not included as predictors.

These stores represent high-performing locations that management should investigate to identify best practices that could be replicated elsewhere.

\---

###### Five Largest Negative Residuals (Over-Predicted Stores)

|Rank|Record (Row)|Predicted Sales|Residual|
|-|-:|-:|-:|
|1|90|747,333.38|**−120,161.48**|
|2|137|748,439.23|**−114,801.20**|
|3|306|650,295.05|**−111,919.05**|
|4|170|690,045.55|**−96,408.41**|
|5|196|539,551.72|**−90,086.66**|

###### Business Interpretation

These stores performed significantly below the model's expectations. Possible reasons include:

* Stock shortages or inventory issues.
* Reduced customer demand.
* Operational inefficiencies.
* Staffing shortages.
* Increased local competition.
* External economic or environmental factors not included in the regression model.

These stores should be reviewed individually to determine the underlying causes of their lower-than-expected performance.

\---

###### Overall Residual Assessment

The residual analysis indicates that the multiple regression model performs well for most observations, but some stores exhibit relatively large prediction errors.

###### Under-Predicted Stores

The model underestimates sales for certain stores, suggesting that there are positive business drivers not included in the regression model. Examples include local promotional campaigns, superior customer service, favorable demographics, or special events.

###### Over-Predicted Stores

The model overestimates sales for some stores, indicating that unobserved negative factors may be affecting performance. These could include operational disruptions, supply-chain issues, stronger-than-expected competition, or temporary declines in customer demand.

\---

###### Model Performance Evaluation

The final multiple regression model explains approximately **78.5%** of the variation in monthly sales (R² = 0.7853), indicating strong predictive performance. However, the residual analysis demonstrates that additional variables could further improve prediction accuracy.

Potential variables for future models include:

* Customer demographics
* Product assortment
* Store size
* Local economic conditions
* Weather
* Competitor promotions
* Seasonal events
* Digital marketing effectiveness

\---

###### Conclusion

Overall, the residuals appear to be reasonably balanced around zero, suggesting that the regression model provides unbiased predictions for most stores. Nevertheless, the presence of several large positive and negative residuals indicates that certain store-specific factors are not fully captured by the current model.

Management should investigate stores with the largest residuals to identify operational strengths and weaknesses. Incorporating additional business variables into future regression models is likely to improve predictive accuracy and provide even stronger decision support.

