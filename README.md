# Breast_Cancer_Detection
This project aims to find out the best possible way to predict Breast Cancer using Machine Learning Algorithms. The different kinds of models that will be used would include Tree Based Classifiers, Regression Based and Probabality Based Models. The best possible model will be decided based on 5 Metrics which are Mean-Accuracy, F1-Score and AUC-Score, Precision and Recall.

## Datasets used:
The datasets used for this project are the Wisconsin Diagnostic and Wisconsin Prognostic Datasets which are available on the UCI Machine Learning Repository. The data in the Dataset has been calculated by measuring the dimensions of the High-Resolution scans of the tissue.

## Methodology:
 1. Data Prerocessing 
 2. Data Visualization
 3. K-Flod Cross-Validation
 4. Model Fitting and Evaluation

Machine learning models used are Logistic regression, Gaussian NB, Random Forest classifier, XGBoostClassifier and K-Nearest neighbors, the performance of individual models is studied over different filters, the effect of resampling data is studied to check if resampling data actually affects the performance of the models of not, the 2nd filter is related to Multicollinearity in the data, the effect of the multi collinear data is also observed with the aim to check if classifiers suffer from performance loss or not when multi-collinear data is present in the dataset. Different files are available for both the datasets Prognostic and Diagnostic datasets, where 4 files consitute to the 4 filters used in the experiment and one file is for Visualisations related to the dataset. Hyperparameter Tuning has not been performed for any model yet. 

## Points of Focus:
 1. No Oversampling 1 (all columns)
 2. No oversampling 2 (dropping columns for multi-collinearity)
 3. Oversampling 1 (all columns)
 4. Oversampling 2 (dropping columns for multi-collinearity)
