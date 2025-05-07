# The Linear Regression Model #

## Overview ##
Linear Regression is a supervised learning algorithm used for predicting a continuous target variable based on one or more predictor variables. 
Regression differs from classification, where the goal is to predict a discrete category or class.

The linear regression model is represented as y=wx+b
where 
$$y$$: predicted value (target)
$$x$$: input feature
$$w$$: weight (coefficient)
$$b$$: bias (intercept)

### Implementation

We use a dataset containing physical dimensions of cars ([text](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction/data)and apply gradient descent to learn a best-fit line. This approach mimics a basic linear regression model using neural network principles. 

We’ll also examine the effect of learning rate on convergence.

We will successfully build a simple regression model using a single artificial neuron and train it via stochastic gradient descent.


### Dependencies

Install the following:
```bash
pip install numpy pandas matplotlib seaborn scikit-learn
