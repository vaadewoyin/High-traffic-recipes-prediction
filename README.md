# High traffic recipes prediction

## Project Background
The product manager would like us to:
-  Predict which recipes will lead to high traffic
-   Correctly predict high traffic recipes 80% of the time

### Success criteria
To correctly predict high traffic recipes at least 80% of the time 

### Modelling:
Since the business problem required us to correctly predict high traffic recipes 80% of the time and minimize the chance of low recipe traffic, the evaluation metric that was used was precision. The two models evaluated were the logistic regression model and random forest model. Logistic regression model served as the baseline model because of its simplicity and interpretability.Random forest is an ensemble model that offers better performance in most cases, and it was compared to the logistic regression model. Since the logistic regression model outperformed the random forest model, it was used as final model.

After threshold tuning, the final model which is the logistic regression model had precision score of about 83.8%. This means that with the model, we are able to correctly predict high traffic recipes 83.8% of the time, This is 3.8% higher than the required metric(or KPI) which is 80%. Therefore, this model solves the required business problem because it can correctly predict high traffic recipes 83.8% of the time.

