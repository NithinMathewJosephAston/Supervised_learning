# Supervised_learning

Task 1:

The file regression1.csv contains 100 pairs of values. The values in the first column are explanatory values/observations. The values in the second column are the 
corresponding response variable values. Using Python, apply least squares regression to fit a line to the data. Plot the data and the fitted line on the same axes.
Calculate the coefficient of determination (the 𝑅2 score) of your prediction and print it. Based on your findings, comment on whether least squares regression is well suited to this 
dataset. Justify your answer.


Task 2:

The file regression2.csv contains 500 rows of three values each. The values in the first and second column are explanatory variables/observations 
and the values in the third column are the corresponding response variable values. You decide to use a multi-layer perceptron (MLP) with a single
hidden layer to fit a model to the data. To implement this, it is recommended that you use scikit-learn’s MLPRegressor. Unless you have a good 
reason to do otherwise, use its default parameter values (except for the size of the hidden layers – see below). One of the parameters we can set
in an MLP is the number of nodes in its hidden layer. The more nodes we have in the hidden layer, the more complexity we can capture in our model.
However, you are aware of the connection between model complexity and overfitting and will want to choose a number of hidden nodes which is high 
enough to capture the complexity in the data, but not so high that your model overfits the data. Based on the principles discussed in lectures, 
design a methodology to:


• choose an appropriate number of hidden nodes for an MLP applied to this regression problem,

• train an MLP with this number of hidden nodes and estimate its generalisation error.

Implement your methodology using Python. Explain your methodology and justify your choice of the number of hidden nodes. You may want to produce 
graphs to help support some aspects of this justification
