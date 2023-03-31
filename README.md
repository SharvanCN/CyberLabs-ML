# CyberLabs-ML
This repository contains the 4 essential machine-learning models namely Linear and Polynomial Regression, Logistic Regression, KNN and Neural networks. 
All files are in the .ipnyb format which can be opened using either Jupyter notebook or Google Colab. All models are implemented from scratch using only numpy, pandas and matplotlib.
### Linear regression:-
The model is trained on the linear_train data set with 20 features. It fits a straight line into the data. The data is normalized. The model has an R2 score of 0.84 on the test set. The final output includes the weights and the bias term in the variables w_final, b_final
### Polynomial Regression:-
The model is trained on the polynomial_train data set. It fits a polynomial of the 5th degree into the data set. The data is normalized and the cost function is regularized. It returns a total of 39 weights and 1 bias in the variables w_final, b_final.
### Logistic Regression:-
The model uses the concept of One-Hot encoding to use BinaryCrossEntropy loss function for multiclassification of 10 classes. The model returns the weights, bias and the accuracy on the test and train sets.
### K - Nearest Neighbour:-
The model uses the same linear_train data set for regression no training of the model is involved and K is set to 4 which gives the best results for the given data set.
### Neural Networks:-
