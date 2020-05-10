# py4linear_regression

Linear Regression Python Library

## Getting Started

This project is simply implementation of linear regression algorithm in python programming language.

### Prerequisites

Numpy


### Installing

The easiest way to install py4linear_regression is using pip

```
pip install py4linear_regression
```

### Usage
There is 2 public method of Linear Regression class. It is learn and predict method, learn method takes 5 argument namely x_train, t_train, alpha, and epoch. It is the training data, it's label, learning rate, and number of iteration respectively. predict method takes 1 argument namely x_test. It is the data to be predicted
```
from py4linear_regression.regression import linear_regression
x_train=[[0,0],[0,1],[1,0],[1,1]]
t_train=[0,1,2,3]
classifier = linear_regression()
classifier.learn(x,t,0.01,250)
x_test=[[0.01,0.99],[0.99,0.01]]
y=classifier.predict(x_test)
```
