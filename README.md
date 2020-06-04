# iris_classification
Machine Learning Project on Iris Dataset using Classification Techniques

## About the dataset:
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.

It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.

The columns in this dataset are:

  * Id
  * SepalLengthCm
  * SepalWidthCm
  *PetalLengthCm
  * PetalWidthCm
  * Species

## Goal of this project:
The main goal of this project is find out which classification model performs well for this dataset.

Our target variable is species.

I will be using the following Classification Techniques:

  1. Logistic Regression
  2. K nearest neighbors 
  3. Desicison tree

## Conclusion

The Decision Tree is the better performing model than Logistic Regression and KNN.

Why so?

Because:

 - Logistic Regression misclassifies some samples.
 - KNN underfits the model.

Since it is a small and clean data set Tree based algorithmns have no problems in classifying the data.

Tunning the hyper parameters using GridSearch technique can help us improve the logistic regression and the KNN model.
