# Predicting-Bank-Subscription


Logistic regression is a type of generalized linear model (GLM) which is mainly used when the response variable is binary, where success is coded as (y=1), and failure is coded as (y=0), where the probability of success is P(Y=1). The random component in logistic model is binomial and the link function is logit (1). 

logit[π(x)] = log [(π(x))/(1-π(x))] = α+β⁡x      equation (1)

π(x) denote the probability of success.
α is the intercept of the graph (for logistic regression its a S-shaped graph).
β is effect parameter, which is used to find the slope, probability and the odds of success, therefore, it shows the rate of increase or decrease of S-shaped curve.

π(x)=  (exp⁡(α+βx))/(1+exp⁡(α+βx))		      equation (2)
Equation 2 is an alternative exponential equation of equation 1, which can be obtained when the logarithmic function is removed from equation 1. 

Equation 1 shows that logit term increases by β for every 1-unit increase in x. This interpretation can also be transformed into odds and odds ratio as follow:
(π(x))/(1-π(x))=exp⁡(α+β⁡x )=exp⁡(α)(exp⁡(β))^x
Here, in this equation exp (β) has multiplicative effect, which means as x increases by 1-unit, the odds of success gets multiply by exp (β)

The final logistic regression equation obtained from the model is:

logit(π (x)) = −121.02 + 0.008(age) − 0.97(conatact-telephone)− 1.78(month-March) – 0.08(campaign) + 1.76(previous subscription-success) – 0.73(emp.var.rate) + 1.29(cons.price.index) + 0.05(cons.conf.endex)
