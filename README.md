# prompt_III

Practical Application 17.1

## Objective

This is a practical exercise involving data from 17 marketing campaigns. The object of the
exercise is to explore the data, clean and prepare it, and then use it to build a set of
machine-learning models that could help a banking institution predict whether customers will
or will not subscribe a term deposit.

The Jupyter notebook can be found here:

## Methods

Exploration of the data involved creating visualizations of the various features and exploration
of correlations within the numerical subset. The data was modeling using Linear Regression, KNN,
SVM, and with a Decision Tree Classifier. The train and test accuracy was compared, fit times were
recorded, and then the models were optimized with GridSearchCV in order to improve performance.

## Findings

Most of the models were comparable in terms of accuracy (i.e. within a few percent), but the
Decision Tree classifier performed significantly better on the training data than on the test
data, so it appeared to be over-fitting without a limit set on the max_depth. KNN and SVM showed
similar accuracies on both training and testing, with KNN standing out as the best overall
performer because it was the fastest.

With further optimization all 3 models could be improved, particularly the Decision Tree Classifier
which showed the overall best accuracy on training data with limits on max_depth and max_features.
