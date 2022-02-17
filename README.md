# Credit-Card-Default-Prediction

## Introduction
Default credit cards are an important issue that brings negative consequences to both sides, i.e, banks and customers. If a customer does not pay his obligations, banks lose money, the customer will lose credibility in future payments, collection calls start to be made and in last resort, the case may go into court. In order to avoid all of that trouble, effective methods that are able to predict the default of credit cards are needed. Therefore, default credit card prediction is an important, challenging, and useful task that should be addressed.

In recent years, the credit card issuers in Taiwan faced the cash and credit card debt crisis and the delinquency is expected to peak in the third quarter of 2006 (Chou,2006). In order to increase market share, card-issuing banks in Taiwan over-issued cash and credit cards to unqualified applicants. At the same time, most cardholders, irrespective of their repayment ability, overused credit card for consumption and accumulated heavy credit and cash–card debts. The crisis caused a blow to consumer finance confidence and it is a big challenge for both banks and cardholders.

## Problem Statement
This project is aimed at predicting the case of customers default payments in Taiwan. From the perspective of risk management, the result of predictive accuracy of the estimated probability of default will be more valuable than the binary result of classification - credible or not credible clients. We can use the K-S chart to evaluate which customers will default on their credit card payments

## Models used 
* Logistic Regression
* SVM
* Random Forest Classification
* XGBoost Classification
* CatBoost Classification
* LightGBM Classification	

## Deployment of Streamlit WebApp in Heroku and Streamlit

We have created front-end using Streamlit.Its deployments and github link are as follows 

| Website | Link |
| ------ | ------ |
| Github | https://github.com/Ali-Asgar-Lakdawala/ML-deployment |
| Heroku | https://my-ml-deployment.herokuapp.com/ |
| Streamlit | https://share.streamlit.io/ali-asgar-lakdawala/ml-deployment/main/app.py |
## Conclusion

* From the project we can conclude that the default rate is higher for males, increases as the education increases, and also increases as the age of a person increases. i.e clients whose age over 60 was higher than mid-age and young people.
In all of these models, our recall revolves in the range of 76 to 84%.with the best fit model as random forest 
* We were successfull in deploying the strealit app on heruko .

