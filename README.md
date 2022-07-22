# WeatherBinaryClassification


This assignment consists of carrying out a binary classification task, and writing a report on this.

The data come from photos, the task is to come up with a machine learning method for classifying the photos according to whether or not it was sunny when they were taken. The data you are given for each photo consists of 4608 features. 4096 of these were extracted from a deep Convolutional Neural Network (CNN), and the remaining 512 are gist features. (You are given all these features as a 1-dimensional array, so you will not be performing any feature extraction on raw images.)

There are two files of training data. The first contains 615 samples with all the data present. The second contains 3000 samples, which have some missing data, as indicated by a NaN (not a number). The training data have class labels, 1 for sunny, and 0 for not sunny. In addition, there is also a confidence label for each sample. The class labels were assigned based on decisions from 3 people viewing the photos. When they all agreed, the class label could be considered certain, and a confidence of 1 was written down. If they didn't all agree, then the classification decided on by the majority was assigned, but with a confidence of only 0.66.

There is one file of test data, containing 2167 samples. The task is to obtain predictions for the class labels of these. (Note that, as with the second training set, the samples in the test data set contain missing features.)

For this assigment, you should reason for which classifier or combination of classifiers you use, such as: SVM, random forest, logistic regression etc. How you do model selection (training-validation split or cross validation), and how you handle the specific issues with these data (large number of features, missing data, the presence of confidence labels for the classes of the training data).
