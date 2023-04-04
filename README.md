# Logistic-Regression

This type of statistical model (also known as logit model) is often used for classification and predictive analytics.
Logistic regression estimates the probability of an event occurring, such as voted or didn’t vote, based on a given dataset of independent variables. 
Since the outcome is a probability, the dependent variable is bounded between 0 and 1. 
In logistic regression, a logit transformation is applied on the odds—that is, the probability of success divided by the probability of failure.
This is also commonly known as the log odds, or the natural logarithm of odds, and this logistic function is represented by the following formulas:

Logit(pi) = 1/(1+ exp(-pi))

ln(pi/(1-pi)) = Beta_0 + Beta_1*X_1 + … + B_k*K_k
