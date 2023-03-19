# Diabetes Analysis with Machine Learning
Diabetes analysis with machine learning involves using a dataset of patients with diabetes and building models that can predict whether a patient has diabetes or not based on certain features. The dataset usually contains features such as age, BMI, blood pressure, insulin levels, and glucose levels.

# README
This repository contains code for the exploratory data analysis (EDA) and classification of diabetes data. The EDA code loads data from the "diabetes.csv" file and performs basic statistical analysis to understand the data. The data distribution is analyzed, and invalid zero values are replaced with suitable values. The data relationship is plotted using a heatmap and a pairplot.

The classification code uses KNN (k-nearest neighbors) algorithm without hyperparameter tuning to classify the diabetes data. The code standardizes the data to bring all features to the same scale. The accuracy is calculated for various values of k neighbors and plotted to determine the best value of k. The classifier is then fit using the best value of k and tested.

# Dependencies
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

# Usage
The code can be run in any Python environment with the dependencies installed. Run EDA.ipynb and Classification.ipynb to perform the EDA and classification, respectively.

# Dataset
The diabetes dataset contains data on females aged 21 years and above from Pima Indian heritage. The dataset has 9 features including glucose, blood pressure, skin thickness, insulin, BMI, age, pregnancies, diabetes pedigree function, and outcome (0 - non-diabetic, 1 - diabetic). The dataset is loaded from the "diabetes.csv" file.

# Results
The EDA results provide insights into the data distribution, data relationship, and invalid values handling. The classification results show the accuracy of the KNN classifier without hyperparameter tuning, KNN classifier with hyperparameter tuning and Logistic Regression with HyperParameter tuning for the diabetes data.

Note that the data is biased towards non-diabetic patients, and the classifier may not perform well for all cases. Further analysis and optimization may be required to improve the classifier's performance.
