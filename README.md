# Customer-Churn-Prediction
Bank customers churn prediction from H2O Auto ML and several machine learning models.

## Context: 
#### Several bank customers leave there account inactive for a period of time, some of these accounts go dormant (Churn) or inactive for long period of time for the customer to have been assumed to have left the bank. This project aim to predict the customers that will Churn based on the avaiable details. Such prediction ability is not only relevant to the banking industry but to small and big business enterprise

### Objectives:
- Identify and visualize which factors contribute to customer churn:
- Classify if a customer is going to churn or not
- Preferably and based on model performance, choose a model that will attach a probability to the churn to make it easier for customer service to target low hanging fruits in their efforts to prevent churn

### Dataset
##### - https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling

## Time Line of the Project:
- Data Analysis
- Feature Engineering
- Model Building using ANN 
- Model Building using SVM
- Model Building and Prediction using H2O Auto ML

## Result summary
- Utilized Decision NN, SVM, and H2O Auto ML to predict customer churn
- All models had good accuracy score raning from 83.3% to 89.4%, with the H2O Auto ML performing better than the others.
- However, SVM had the lowest False Negatives with H2O Auto ML closely behind. False Negatives indicate how well we avoid wrongly predicting the customers who churned as did not churn. 
- On the other hand, H2O Auto ML had the best prediction of customers that will shurn(67%) 

![H20 Auto ML result](https://user-images.githubusercontent.com/112252681/194196663-c8504778-453b-43f5-8b8a-6d80bc3b8e2c.PNG)
