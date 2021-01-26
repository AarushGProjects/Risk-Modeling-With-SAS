# Risk Modeling With SAS

Lending club is an American peer to peer lending company. There has been a significant increase in the delinquency rate. The company would like to develop a business strategy 
in order to reduce the default rate. The dataset provided by the company consists of 300000 records and 151 features.  

# Credit Risk Modeling 

A credit scoring model is used in evaluating a credit application. Credit lending firms can save millions of dollars by assessing an applicant’s profile before approving a loan. The model estimates the probability of default using a machine learning algorithm. The model can assess the profiles of existing as well as the new clients. We will use logistic regression to predict the probability of default.


Logistic Regression is a probabilistic technique that uses a logit function for binary classification.
Logit = log(odds) = Bo+B1…Bn


             We get, P = 1/1+exp(-y)
             
             
             P = exp(Bo+B1…Bn)/1+exp(Bo+B1…Bn) 
             
             
Where P: Probability of default


             Bi: Regression coefficient of explanatory variables
