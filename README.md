# Simple-Linear-Regression
The project aims to use Simple Linear Regression to evaluate the importance of two input features in the Boston Housing Dataset.
The dataset contains the following input features(independent variables):
- CRIM     per capita crime rate by town
- ZN       proportion of residential land zoned for lots over 25,000 sq.ft.
- INDUS    proportion of non-retail business acres per town
- CHAS     Charles River dummy variable (= 1 if tract bounds river; 0 otherwise)
- NOX      nitric oxides concentration (parts per 10 million)
- RM       average number of rooms per dwelling
- AGE      proportion of owner-occupied units built prior to 1940
- DIS      weighted distances to five Boston employment centres
- RAD      index of accessibility to radial highways
- TAX      full-value property-tax rate per $10,000
- PTRATIO  pupil-teacher ratio by town
- B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town
- LSTAT    % lower status of the population

Also, the dataset contains the following target variable(to be predicted/dependent variable).
- MEDV     Median value of owner-occupied homes in $1000's

In this project, two linear regression models are built using the following input features in each:
- RM
- LSTAT

The model is build using the **Scikit-Learn** python library for machine learning and the performance of the models are compared using scatter plots and statistical metrics.

In conclusion, it was determined that the model fitted on **LSTAT** input feature has better performance as compared to the **RM** input feature.
