# Unit11 - Machine Learning: Classification

In this assignment built and evaluated machine learning models to predict credit risk using data that one would typically see from peer-to-peer lending services. Credit risk is an inherently imbalanced classification problem (the number of good loans is much larger than the number of at-risk loans), so we had to employ different techniques for training and evaluating models with imbalanced classes. We have used the imbalanced-learn and Scikit-learn libraries to build and evaluate models using the two following techniques:

1. Resampling

In this exercise we split the data into training an testing (created our features and target), followed by:

* We used StandardScaler from sklearn to fit and scale the training and testing data. 
* We ran the Simple Logistic Regression to calculate the balanced accuracy score, display the confusion matrix, and print the imbalanced classification report.
* We then moved onto Oversampling using the Naive Random Oversampler, and SMOTE algorithms
* Followed by undersampling using the Cluster Centroids algorithm.
* And over and undersampled using the combination SMOTEEN algorithm.

2. Ensemble Learning

In this exercise we split the data into training an testing (created our features and target), followed by:

* We used StandardScaler from sklearn to fit and scale the training and testing data. 
* Then we compared two ensemble algorithms determine which algorithm results in the best performance.
* We trained a Balanced Random Forest Classifier and an Easy Ensemble classifier.

Based on teh results from each of our exercises we were able to answer the questions asked in the assignment (the answers are in each of the respective Jupyter notebooks).
