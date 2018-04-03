# Employee-Attrition--XGBoost-SVM-XGB-
Employee attrition Classification using Sklearn.
As we learned above why attrition plays a pivotial role we will learn how to classify it using various algorithms.

Maintaining the attrition rate is pivotial for the industry. More and More companies are investing in Human Resource attrition to keep a tap on the attrition rate.
We are feature construting the variable which are most pivotial for predicting attrition.
1)Gradient Boosting Classifier
We have hyper parameter optimized the Gradient Boosting Classifier as it would increase the accuracy.
* max_depth = The range of this must be between 1 and 6. Keeping the depth more would cause the tree to be overfit the data. This process is know as prunning. Here we are manually prunning the tree rather than automatically prunning it.
* Learning_rate = Kept the learning rate to be low to avoid huge errors .
* n_estimators = These are the number of trees or models which we want to run.

2)Neural Network
We have hyper parameter optimized the Neural Network.
* Hidden Layer Size: Kept the hidden layer sizer incremental increasing as we move to the next layer.
* No of Iteration: Maximum iterations have kept it 2500 so as the model has enough iterations to learn.
* Learning Rate: Kept the learning rate and momentum both small as it will reduce the errors.
* Solver: The method is adam which is a optimization method and is a mix of adaptive gradient descent and Root Mean Square Propogation.

CONCLUSION:

1) SVM -- 0.71 -- 71%

2) XGB -- 0.82 -- 82%

3) NN -- 0.84 -- 84%

We can conclude that Neural Network is the best model!!
