# **Machine Learning from Scratch**

## Different classification and regression Machine Learning models implemented from scratch. 
-------------------------------------------------------------------------------
- **logistic_regression**: creating a learning machine (logistic regression algorithm) to predict the probability of an observation having a high coverage of miles per gallon of fuel (label 1) or a low coverage (label 0). For this we create a variable ‘high’ that takes the value 1 if miles per gallon variable ‘mpg’ is greater than 23; 0 otherwise.
I am using gradient descent to find the optimum values for the parameters of the learning machine, which minimizes the negative log-likelihood or the error of our model. Given initial parameter for the weights or coefficients (lamdas), number of iterations (epochs), learning rate (eta) we apply our model to predict the probabilities of ‘high’ being 1. We choose the following criteria for getting the predicted labels: The learning machine will assign the label 1 if the probability is greater or equal to 0.5; 0 otherwise.

- **random_forest**: this is an implementation of Random Forest algorithm from scratch tested  in the Boston housing prices. for accuracy testing the accuracy of our models we use the Mean Squared Error metric. The machine learning model has two hyper parameters: the number of trees and the height of the decision trees. We test our model for different values of those parameters. 

- **agg_hierarchical_clustering**: implementing Agglomerative Hierarchical clustering from scratch with the following distance metrics: single, complete, average and centroid linkage. I apply my model to the  NCI microarray dataset whose columns are 6830 and the number of rows are 64. ‘k’ represents the number of clusters we want to form. For k=10 we can see that complete and centroid linkage form more even clusters and the linkage with the worse performance is single linkage.
