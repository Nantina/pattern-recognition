# Pattern Recognition
This repository contains a Python implementation of multiple Algorithms for Multiclass Classification. Specifically, four Classifiers have been implemented:
- Bayesian Classifier using the Maximum Likelihood technique
- K-Nearest Neighbor Classifier 
- Support Vector Machines (Linear and non Linear Kernels)
- Multilayer Perceptron Neural Network using the back propagation algorithm


## Datasets 

The first three classifiers are trained on a dataset with two features and multiple classes (`dataaset.csv` file), while the last one is trained on a 400 feature dataset with six classes (`datasetC.csv` file).

## Bayesian Classifier
The `Bayes_Classifier.ipynb` file contains:
- The functions and logic for classification using the Maximum Likelihood technique.
- Results where the classifier uses the same covariance matrix for all classes and when each class has a different covariance matrix.
- Plots for desicion boundaries for the classes.

## K-Nearest Neighbor Classifier 
The `Knn.ipynb` file contains:
- The K-NN classification functions from the sklearn library.
- Classification Report and Decision Boundaries for k = 1, ..., 10 neighbors.

## Support Vector Machine Classifier
The `SVM.ipynb` file contains:
- The Linear Kernel SVM functions from the sklearn library.
- The RBF Kernel SVM functions from the sklearn library.
- Classification Report and Error for different sets of hyperparameters.
- Plots for Correclty classified samlpes, missclassified samples and decision boundaries for both kernel types.

The hyperparameters used were conducted with GridSearch and were found to produce the best results. 

## Multilayer Perceptron
The `ML_NN` file contains:
- A Layer Class with forward and backward pass functions as well as updates function.
- Training with Different sets of hyperparameters. 
- Plots for Training Accuracy, Test Accuracy, Training Time and Loss for different sets for easy comparison.
- Final Training and Testing with the beast hyperparameters.
