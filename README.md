# Olist-Review-score-prediction
ML Classification problem for Brazilean e-commerce company "Olist".  
Predicting review score for each customer order (1-5). 

__Motivation:__  
Dynamically predicting customer satisfaction for their oder will serve two purposes: 
1. Allow for additional action by the company in order to minimize dissatisfaction. e.g. emitting a coupon to the customer every time he is predicted to have a review score < 2/5
2. Better identify drivers of dissatisfaction. Although we cannot imply causality without a proper causality analysis, knowing feature importance of predicting review scores can give an idea of which features are related.
4. Compaaring different feature engineering alternatives as well as ML classification models for this particular problem.
5. EDA provides BI descriptive analytics on how the company is performing in relation to review scores.

__Models trained:__
- Random Forest Classifier
- Logistic Regression
- XGBoost Classifier

Original dataset on: https://www.kaggle.com/olistbr/brazilian-ecommerce
