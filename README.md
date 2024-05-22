## Phase_3_project
Classification project to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company.


#### Background

SyriaTel is one of the leading telecommunication companies in Syria. 
It provides a wide range of telecommunications services, including mobile and fixed-line telephony, internet services and data services.

### Business Understanding
Syriatel has been a key player in the Syrian telecommunications market, serving millions of customers across the country. The company has played a significant role in expanding and modernizing telecommunications infrastructure, contributing to the country's connectivity and economic development. 

The telecommunications company is interested in reducing how much money is lost because of customers who don't stick around very long.

 Problem Statement
In this competitive world, business is becoming highly saturated. Especially, the field of telecommunication faces complex challenges
due to a number of vibrant competitive service providers. Therefore, it has become very difficult for them to retain existing customers. Since the cost of
acquiring new customers is much higher than the cost of retaining the existing customers, it is the time for the telecom
industries to take necessary steps to retain the customers to
stabilize their market value.

### Data Understanding

The number of rows in the SyriaTel dataframe is 3333
The number of columns in the SyriaTel dataframe is 21

       Observations
The minimum number of voicemail messages, total day minutes, total day calls, total day charge, total evening minutes, total evening calls and total evening charge are all 0.
There are 483 disloyal customers who have churned the services of SyriaTel.
No column had a missing value.
There are 51 unique states represented in this Dataframe.
The churn rate was observed to be at 14.49%.
The churn rate currently stands at 14.49% 


### Modelling

The first model, Logistic regression, which was the baseline model gave an accuracy of 85%
The second model will be still Logistic Regression but with additional hyper parameters, and this model gave an accuracy of 86% which was a very slight improvement.
The third model will entail ensemble methods yielding better accuracies on different models.

* ###### Gradient Boosting

Training accuracy for Gradient Boosting: 0.9542396582133497

Test accuracy for Gradient Boosting: 0.9505247376311844

* ###### XGBoost

Training accuracy for XGBoost: 0.9534905945429376

Test accuracy for XGBoost: 0.9535232383808095


### Model Evaluation

Based on the Ensemble methods metrics, Gradient Boosting and XGBoost not only performed well on training data but also generalized effectively to unseen test data, suggesting a good balance between underfitting and overfitting.
Consequently, SyriaTel should prioritize deploying Gradient Boosting and XGBoost models for their churn prediction system.


 #### Next Steps:
 Based on the insights derived from the models and feature importance analysis, SyriaTel can implement the following customer retention strategies:
 Proactive Customer Support: This could involve regular check-ins or offering dedicated support channels.
 Personalized Offers and Discounts: Use predictive models to identify customers at high risk of churn and provide them with personalized offers, discounts, or 
 loyalty programs to enhance their satisfaction and loyalty.
 Improved Service Plans: Evaluate and potentially revamp service plans based on the usage patterns identified as critical churn factors. For instance, if customers 
 with low voice mail plan usage are more likely to churn, consider bundling voice mail services with other popular plans.


### CONCLUSION
By leveraging the high-performing Gradient Boosting and XGBoost models, SyriaTel can gain valuable insights into customer behavior and implement targeted retention strategies to reduce churn. Continuous monitoring, model updates, and integration with CRM systems will further enhance the effectiveness of these efforts, ultimately contributing to increased customer retention and sustained business growth.
