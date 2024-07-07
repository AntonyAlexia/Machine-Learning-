# Machine-Learning

Machine Learning Project Overview
This project showcases a comprehensive application of various machine learning techniques using Python, focusing on both regression and classification methods, along with an advanced implementation of face recognition using Principal Component Analysis (PCA). The project is structured into three main parts: Regression Analysis, Classification, and Face Recognition.

Part 1: Regression Analysis
Linear Regression by Least Squares
The project begins with an analysis of the correlation between female illiteracy rates and fertility rates across different nations. Using linear regression by least squares, the relationship is examined, and the Pearson correlation coefficient is computed to quantify the strength and direction of the linear relationship.

Anscombe's Quartet
To emphasize the importance of data visualization and exploratory data analysis (EDA), Anscombe's quartet is analyzed. This set of four datasets has nearly identical summary statistics but different distributions. Linear regression is performed on one dataset to illustrate the significance of graphical analysis in understanding data properties.

Linear Regression on All Anscombe Data
Expanding the analysis of Anscombe's quartet, linear regression is performed on all four datasets. The project verifies that each dataset yields the same slope and intercept, despite their differing distributions, reinforcing the lesson on the limitations of relying solely on summary statistics.

Regression Using Scikit-Learn
The project transitions to using the scikit-learn library for regression tasks. A simple linear regression example is provided, demonstrating the usage of the fit() and predict() methods, highlighting the efficiency and workflow orientation of scikit-learn for machine learning tasks.

Polynomial Regression
To handle nonlinear relationships, polynomial regression is introduced. The project demonstrates how to transform data using polynomial basis functions and perform regression with a polynomial of degree seven. The use of scikit-learn's PolynomialFeatures transformer and pipeline for streamlining the process is showcased.

Regularization
Addressing the issue of overfitting in high-degree polynomial regression, the project explores regularization techniques. A 15th-degree polynomial fit to sinusoidal data is used to illustrate overfitting and the necessity of regularization to improve model generalization.

The Housing Problem
Using the Boston housing dataset, the project presents a practical application of linear regression. The dataset is loaded and converted into a Pandas DataFrame. Two features, LSTAT (percentage of lower status population) and RM (average number of rooms per dwelling), are selected to fit a model. The data is split into training and testing sets, following a typical machine learning workflow.

Part 2: Classification
The Iris Dataset
The Iris dataset, containing measurements of different Iris flower species, is utilized for classification tasks. The project loads the dataset, visualizes the data through histograms and pair plots, and computes summary statistics to understand the distributions of features among the species.

Digit Classification
For a more complex classification task, the MNIST dataset of handwritten digits is used. The dataset consists of 60,000 training examples and 10,000 test examples, each image being 28x28 pixels. The project includes loading the images, flattening and normalizing them, and displaying a few samples, setting the stage for classification algorithms.

Part 3: Face Recognition Using PCA (Eigenfaces)
The final part of the project involves an advanced machine learning application: face recognition. Using a subset of the Labeled Faces in the Wild (LFW) dataset, the project applies Principal Component Analysis (PCA) to perform face recognition. The dataset is loaded, images are resized, and PCA is used to reduce the dimensionality of the data, creating "eigenfaces" for recognition tasks. This section demonstrates the application of PCA in handling high-dimensional data and its effectiveness in image recognition tasks.
