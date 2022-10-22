# Day 10
## Linear regression

Scikit-learn is a powerful Python module for machine learning. It contains function for regression, classification, clustering, model selection and dimensionality reduction.

The first step is to import the required Python libraries into Ipython Notebook.

`%matlotilib inline`

`import numpy as np`

`import panda as pd`

`import scipy.stats as stats`

`import matplotlib.pyplot as plt`

`import sklearn`

This data set is available in sklearn Python module, so I will access it using scikitlearn. I am going to import Boston data set into Ipython notebook and store it in a variable called boston.

`from sklearn.datasets import load_boston`

`boston = load_boston()`

This data set is available in sklearn Python module, so I will access it using scikitlearn. I am going to import Boston data set into Ipython notebook and store it in a variable called boston.

`boston.key()`

### benifits of lenear regression

Linear regression is one of the fundamental statistical and machine learning techniques. Whether you want to do statistics, machine learning, or scientific computing, there’s a good chance that you’ll need it. It’s best to build a solid foundation first and then proceed toward more complex methods.

### Regression

Regression analysis is one of the most important fields in statistics and machine learning. There are many regression methods available. Linear regression is one of them.

### What Is Regression?

Regression searches for relationships among variables. For example, you can observe several employees of some company and try to understand how their salaries depend on their features, such as experience, education level, role, city of employment, and so on.

### When Do You Need Regression?

Typically, you need regression to answer whether and how some phenomenon influences the other or how several variables are related. For example, you can use it to determine if and to what extent experience or gender impacts salaries.

Regression is also useful when you want to forecast a response using a new set of predictors. For example, you could try to predict electricity consumption of a household for the next hour given the outdoor temperature, time of day, and number of residents in that household.

### Linear Regression

Linear regression is probably one of the most important and widely used regression techniques. It’s among the simplest regression methods. One of its main advantages is the ease of interpreting results.

![l_reg](../../asset/fig-lin-reg.png)

> ## Referances

1- http://bigdata-madesimple.com/how-to-run-linear-regression-in-python-scikit-learn/

2- https://realpython.com/linear-regression-in-python/