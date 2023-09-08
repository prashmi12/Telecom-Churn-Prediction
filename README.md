# Project Name : Telecom Churn Prediction
> This is the case study for a advance understanding of unsupervised learning, using PCA.

## Table of Contents
* [General Info](#general-information)
* [Libraries Used in Python](#libraries-used)

## General Information <a name="general-information"></a>
In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, we will analyze customer-level data of a leading telecom firm, and build predictive models to identify customers at high risk of churn.

In this case study, our goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage.

**Understanding Customer Behaviour During Churn**

Customers usually do not decide to switch to another competitor instantly, but rather over a period of time (this is especially applicable to high-value customers). In churn prediction, we assume that there are three phases of customer lifecycle :

- *The ‘good’ phase:* In this phase, the customer is happy with the service and behaves as usual.

- *The ‘action’ phase:* The customer experience starts to sore in this phase, for e.g. he/she gets a compelling offer from a competitor, faces unjust charges, becomes unhappy with service quality etc. In this phase, the customer usually shows different behaviour than the ‘good’ months. Also, it is crucial to identify high-churn-risk customers in this phase, since some corrective actions can be taken at this point (such as matching the competitor’s offer/improving the service quality etc.)

- *The ‘churn’ phase:* In this phase, the customer is said to have churned. You define churn based on this phase.

*In this case, since we are working over a three-month window, the first two months are the ‘good’ phase and 'action' phase, the third month is the ‘churn’ phase.*

**Goal:**
It is our job to predict if a customer will churn, given the ~170 columns containing customer behavior, usage patterns, payment patterns, and other features that might be relevant. Our target variable is "churn_probability".

**We are going to solve the problem in 4 sections i.e. :**
- Data understanding and exploration
- Data Visualisation and Data preparation
- Model selection, model building, evaluation & prediction
- Final Insights and Conclusion
- Evaluating final model on the Kaggle test data

## Libraries Used in Python <a name="libraries-used"></a>
- numpy 
- pandas
- matplotlib.pyplot
- seaborn 
- missingno
- sklearn
- statsmodels
- imblearn
- xgboost
