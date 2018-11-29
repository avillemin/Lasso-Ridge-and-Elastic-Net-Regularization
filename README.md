# Lasso Ridge and Elastic Net Regularization

[Source] https://medium.com/@jayeshbahire/lasso-ridge-and-elastic-net-regularization-4807897cb722

Regularization techniques in Generalized Linear Models (GLM) are used during a modeling process for many reasons. A regularization technique helps in the following main ways:   
- Doesn’t assume any particular distribution of the dependent variable ( DV). The DV can follow any distribution such as normal, binomial, possison etc. Hence the name Generalized Linear Models (GLMs)
- Address Variance-Bias Tradeoffs. Generally will lower the variance from the model
- More robust to handle multicollinearity
- Better sparse data (observations < features) handling
- Natural feature selection
- More accurate prediction on new data as it minimizes overfitting on the train data
- Easier interpretation of the output
<p align="center"><img src="https://cdn-images-1.medium.com/max/1000/0*NxgH5J_36pSFE0O-." width="350" height="350"></p>

What is a regularization technique you may ask? A regularization technique is in simple terms a penalty mechanism which applies shrinkage (driving them closer to zero) of coefficient to build a more robust and parsimonious model. Although there are many ways to regularize a model, few of the common ones are:   
- L1 Regularization aka Lasso Regularization– This add regularization terms in the model which are function of absolute value of the coefficients of parameters. The coefficient of the paratmeters can be driven to zero as well during the regularization process. Hence this technique can be used for feature selection and generating more parsimonious model   
- L2 Regularization aka Ridge Regularization — This add regularization terms in the model which are function of square of coefficients of parameters. Coefficient of parameters can approach to zero but never become zero and hence   
- Combination of the above two such as Elastic Nets– This add regularization terms in the model which are combination of both L1 and L2 regularization.   
