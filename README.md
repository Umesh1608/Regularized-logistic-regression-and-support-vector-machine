# Regularized-logistic-regression-and-support-vector-machine

### Problem1.py file corresponds to Regularized logistic Regression

Train and test a regularized logistic regression model one two data sets, namely the breast
cancer and sonar data sets which are available here
https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html #breast-cancer 
and here https://www.csie.ntu.edu.tw/~cjlin/libsvmtools/datasets/binary.html #sonar. 
We will use the scaled version for our experiment. A copy of them is also enclosed in the Data file. Use the provided train-
ing/testing splitting. In particular, the file "xxx-scale-test-indices.txt" contains the indices of
examples in the original file for training, and "xxx-scale-test-indices.txt" contains the indices
of examples in the original file for testing.

- Use the 5-fold cross validation method to decide the best value of the parameter C. The
candidate values for C are 0:1, 1; 10; 100; 1000. For each C, report the training error and
validation error. Choose the best C that yields the lowest validation error.
- Use the selected best C value to train a logistic regression model on the whole training
data and evaluate and report its performance (by error rate) on the testing data.
