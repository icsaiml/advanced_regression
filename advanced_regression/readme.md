Advanced Regression Assignment

Predicting house prices using advanced regression techniques such as Ridge and Lasso.

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. The data is provided in the 'test.csv' file uploaded in the repository.

The company is looking at prospective properties to buy to enter the market. This repository builds a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.

The company wants to know: 

-Which variables are significant in predicting the price of a house? 

-How well those variables describe the price of a house?

By employing GridSearchCV, the model systematically identifies the optimal lambda values for determining house prices through Ridge and Lasso regression. This meticulous approach allows for an automated search across a predefined hyperparameter grid, enabling the model to fine-tune lambda and optimize its predictive performance in the context of regression