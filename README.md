# k-fold-cross-validation
What is K-Fold Cross Validation?

K-Fold CV is where a given data set is split into a K number of sections/folds where each fold is used as a testing set at some point. Lets take the scenario of 5-Fold cross validation(K=5). Here, the data set is split into 5 folds. In the first iteration, the first fold is used to test the model and the rest are used to train the model. In the second iteration, 2nd fold is used as the testing set while the rest serve as the training set. This process is repeated until each fold of the 5 folds have been used as the testing set.

![grid_search_cross_validation](https://user-images.githubusercontent.com/29706431/209469847-f56096a5-8db0-4d0a-a56b-3a6953801a53.png)
