# machine_learning_from_scratch
Different classification and regression Machine Learning models implemented from scratch. 
-------------------------------------------------------------------------------
LOGISTIC REGRESSION: creating a learning machine (logistic regression algorithm) to predict the probability of an observation having a high coverage of miles per gallon of fuel (label 1) or a low coverage (label 0). For this we create a variable ‘high’ that takes the value 1 if miles per gallon variable ‘mpg’ is greater than 23;  0 otherwise.
 I am using gradient descent to find the optimum values for the parameters of the learning machine, which minimizes the negative log-likelihood or the error of our model. Given initial parameter for the weights or coefficients (lamdas), number of iterations (epochs), learning rate (eta) we apply our model to predict the probabilities of ‘high’ being 1. We choose the following criteria for getting the predicted labels: The learning machine will assign the label 1 if the probability is greater or equal to 0.5; 0 otherwise.
