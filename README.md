# Credit_Risk_Analysis

Overview:
    Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.

Results:
    The analysis was separated into two parts: resampling methods and ensemble classifiers. The data was sourced from a "LoanStats_2019Q1.csv" CSV file, where it was filtered, split into training and testing sets, and utilized in predicting results via a logistic regression model. The evaluation of these predictions was conducted using the "balanced_accuracy_score," alongside the creation of a confusion matrix and imbalanced classification report.

Summary:
    After assessing the results obtained from testing each of the models, we would recommend utilizing the ensemble approach if we were to select only one, as it provided the highest accuracy for the high-risk individual variable. However, it is not recommended to use any of these models for commercial purposes due to their overall inaccuracy in predicting high-risk variables, all of which were less than 10%.