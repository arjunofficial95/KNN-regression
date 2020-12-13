1. Implement the KNN regressor function:
knn(train.data, train.label, test.data, K=3) which takes the training data and their labels (continuous values), the test set, and the size of the neighborhood (K). It should return the regressed values for the test data points. We used a distance function to choose the neighbors. The distance function used to measure the distance between a pair of data points is Manhattan distance function.

2. Plot the training and the testing errors versus 1/K for K=1,.., 30 in one plot, using the Task1A_train.csv and Task1A_test.csv datasets provided.

3. Reporting the optimum value for K in terms of the testing error.
