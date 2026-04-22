# Loan Prediction Project

In this project, I worked on a loan dataset to predict whether a loan will be fully paid or not.

## Steps I followed:
- Loaded and explored the dataset using pandas
- Performed exploratory data analysis (EDA) using seaborn and matplotlib
- Converted categorical features into dummy variables
- Split the data into training and testing sets
- Trained multiple models including KNN, Decision Tree, and Random Forest
- Evaluated the models using confusion matrix and classification report

## Key Findings:
The models performed well for predicting the majority class (fully paid loans), but struggled with the minority class (not fully paid).  
This is mainly due to class imbalance in the dataset.

Random Forest performed better than Decision Tree overall, providing more stable and accurate predictions.

## Conclusion:
Model performance can be improved by handling class imbalance using techniques such as resampling or adjusting class weights.