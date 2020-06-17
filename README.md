# Marketing Mailing Predictive Analytics (PySpark)
This is a group project. Team 4JH includes Jing Li, Jiayin Liu, Jacqueline Huang, Jack Ye, Han Lu.


### Goal
This project aims to achieve 1.5 million revenue increase through sending marketing mailings to potential customers with the lowest cost. The goal is to bulid a classification model identifying customers who are most likely to respond to marketing mailings for new product promotion.


### Dataset
The project idea and [dataset](https://relational.fit.cvut.cz/dataset/SAP) are from SAP.


### Analysis 
- We utilized EDA to select variables after dataset combination and cleaning. In addtion, we used feature engineering to extract useful features for model building. 

- Then we developed a logistic regression model to classify customers according to their demographic information and transaction history. 

- In order to get enough true responses with the lowest cost, we plotted threshold vs. true positives to determine the best threshold. 

- Finally we utilized the logistic regression model with best threshold to identify potential customers in the "future dataset".

### Result
The model flagged 5,022 customers, which potentially leads to 1,667 true responses and 1.5 million revenue increase. By conducting this project, the marketing mailing response rate improved from 5% to 33%, and the marketing expenses were saved by 76%!
