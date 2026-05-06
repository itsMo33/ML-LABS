# Support Vector Machine (SVM) - Iris Dataset Assignment

## Overview
This project applies Support Vector Machine (SVM) classification on the famous
Iris flower dataset using Python and Scikit-Learn.

## Dataset
The Iris dataset contains 150 samples from three species of Iris flowers:
- Iris-setosa (n=50)
- Iris-versicolor (n=50)
- Iris-virginica (n=50)

Four features are measured for each sample:
- Sepal length (cm)
- Sepal width (cm)
- Petal length (cm)
- Petal width (cm)

## Libraries Used
- numpy
- pandas
- matplotlib
- seaborn
- scikit-learn

## Project Steps

### 1. Exploratory Data Analysis (EDA)
- Loaded the Iris dataset using Seaborn
- Created a pairplot to visualize feature relationships by species
- Created a KDE plot of sepal length vs sepal width for Iris Setosa
- **Finding:** Iris Setosa is the most separable species

### 2. Train/Test Split
- Split data: 70% training, 30% testing
- Used `random_state=101` for reproducibility

### 3. Model Training
- Trained an SVM classifier using `SVC()` from Scikit-Learn
- Used default RBF kernel

### 4. Model Evaluation
- Generated confusion matrix and classification report
- **Result:** 98% overall accuracy with only 1 misclassification

### 5. Hyperparameter Tuning (GridSearchCV)
- Tuned `C` values: [0.1, 1, 10, 100]
- Tuned `gamma` values: [1, 0.1, 0.01, 0.001]
- Tested 16 combinations with 3-fold cross-validation (48 total fits)
- **Result:** No improvement needed — default model was already optimal

## Results

| Metric    | Score |
|-----------|-------|
| Accuracy  | 98%   |
| Precision | 0.98  |
| Recall    | 0.98  |
| F1-Score  | 0.98  |

## How to Run
1. Clone the repository
2. Install dependencies: