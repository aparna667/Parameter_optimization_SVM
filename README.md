## Overview

This code uses the Nu-Support Vector Classification (NuSVC) algorithm from the Scikit-Learn library to classify letter images. The dataset used in this code is the Letter Recognition dataset from the UCI Machine Learning Repository. The NuSVC algorithm is used with different kernel functions to find the best kernel, nu, and epsilon values for each sample of the dataset. The best parameters are then used to predict the classes of the test data and the accuracy of the classification is calculated.

## Dataset
The Letter Recognition dataset used in this code is available on the UCI Machine Learning Repository at https://archive.ics.uci.edu/ml/datasets/Letter+Recognition. This dataset consists of 20,000 handwritten letters from A to Z, with each letter represented by 16 attributes (8x16 matrix of integers) and one target variable indicating the class label of the letter.

## Running the code:
To run this code, follow these steps:

Download the code file from the repository.
Open a terminal or command prompt and navigate to the directory where the code file is saved.
Type "python filename.py" in the terminal and press Enter.
The code will start running and will output a table showing the best accuracy, kernel, nu, and epsilon values for each sample. Additionally, a convergence graph will be generated showing the accuracy of the NuSVC algorithm for the sample with the highest accuracy.

## Results:
The code outputs a table showing the best accuracy, kernel, nu, and epsilon values for each sample. The convergence graph shows the accuracy of the NuSVC algorithm for the sample with the highest accuracy. By analyzing the results, you can determine which kernel function and parameter values work best for the classification of the letter images.
![Convergence graph](https://github.com/aparna667/Parameter_optimization_SVM/blob/main/convergence_graph.png)


## Further Improvements:
This code can be improved in several ways, including:

Using different classification algorithms to compare their performance with the NuSVC algorithm.
Tuning more hyperparameters of the NuSVC algorithm to further improve the accuracy of the classification.
Using different datasets to classify other types of images or data.
Applying feature engineering techniques to extract more meaningful features from the image data.
Using deep learning techniques such as convolutional neural networks (CNNs) to classify the image data with higher accuracy.
