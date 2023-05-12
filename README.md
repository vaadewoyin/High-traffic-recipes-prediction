# High-traffic-recipes-prediction-project

# Project Background
The product manager would like us to:
-  Predict which recipes will lead to high traffic
-   Correctly predict high traffic recipes 80% of the time

## Success criteria
To correctly predict high traffic recipes at least 80% of the time 

## Modelling:
Since the business problem required us to correctly predict high traffic recipes 80% of the time and minimize the chance of low recipe traffic, the evaluation metric that was used is precision.The two models evaluated were the logistic regression model and random forest model.Logistic regression model served as baseline model because of its simplicity and interpretability. random forest is an ensemble model that offers better performance in most cases, and it was compared to the logistic regression model.since the logistic regression model outperformed the random forest model, it was used as final model.after threshold tuning

The final model which is the logistic regression model had precision score of about 83.8%. This means that with ther model, we were able to correctly predict high traffic recipes 83.8% of the time, This is 3.8% higher than the required metric(or KPI) which is 80%. Therefore, this model solves the required business problem because it can correctly predict high traffic recipes 83.8% of the time.

