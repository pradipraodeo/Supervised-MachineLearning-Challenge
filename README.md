# Supervised-MachineLearning-Challenge
### Predicting Credit Risk
### Background
Lending services companies allow individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market.
In this challenge, this data was used to create machine learning models to classify the risk level of given loans. 
### Consider the models
You will be creating and comparing two models on this data: a logistic regression, and a random forests classifier. Before you create, fit, and score the models, make a prediction as to which model you think will perform better. You do not need to be correct! Write down (in markdown cells in your Jupyter Notebook or in a separate document) your prediction, and provide justification for your educated guess.

### Fit a LogisticRegression model and RandomForestClassifier model

In this dataset, we created the Logistic Regression model and Random Forest Classifier.

For the Logistic Regression model, the score of the hypertuned model on the test dataset is 0.9924680148576145. This indicates the logistic Reression model can fit in the 99% of the testing data. The scores of the Logistic regression model without hyperparameters are also high (Training Data Score: 0.9919177328380795,Testing Data Score: 0.9924680148576145), and the accuracy is 99%.

For the Random Forest Classifier,the Training Score is 0.9971970009629936 and the Testing Score is 0.991900536524969. This indicates the Random Forest Classifier also can fit in the 99% of the testing data. The most important feature to indicate high risk of loan is the interest rate. The higher interest rate indicates higher credit risk.

To conclude, both of the models can perform good to predict the risk.