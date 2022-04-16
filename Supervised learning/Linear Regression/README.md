**Introduction**  

- Gradient Descent  
  - In the machine learning algorithm, when minimizing the loss function, the gradient descent method can be used to iteratively solve step by step to obtain the minimized loss function and the value of model parameters. Conversely, if we need to solve the maximum value of the loss function, we need to use the gradient rise method to iterate. 
  - Related concepts of gradient descent  
    1. Learning rate: the step determines the length of each step along the negative direction of the gradient in the process of gradient descent iteration.
    2. Feature: refers to the input part of the sample
    3. Hypothesis function: a function used to fit input samples in supervised learning
    4. Loss function: in order to evaluate the quality of model fitting, the loss function is usually used to measure the degree of fitting.
- Linear Regression

  - The regression algorithm is relative to the classification algorithm, which is related to the value type of the target variable y we want to predict. If the target variable y is a classified variable, such as predicting the gender of users, predicting the color of flowers, and predicting whether we have a disease, we need to use the classification algorithm to fit the training data and make a prediction; If y is a continuous variable, such as predicting the income of users, predicting the probability of employee turnover, and predicting the probability of lung cancer, we need to use a regression model.   
  - Linear regression is a kind of regression algorithm. If there is a "linear relationship" between two or more variables, find out the "routine" between variables through historical data, and the established model is a linear regression model.


**DataSet**  
The data used in Lecture 4 is

- Wheat seed dataset:

  - Similar to iris dataset. The data set contains seed information belonging to three different wheat varieties: Kama, Rosa and Canadian, represented by 1, 2 and 3 respectively
  - Link:https://www.kaggle.com/datasets/jmcaro/wheat-seedsuci
