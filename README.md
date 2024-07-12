
# Supervised-Learning


This project demonstrates the application of supervised learning techniques to solve classification and regression problems. The aim is to predict outcomes based on labeled training data using various machine learning algorithms. Key components of the project include data preprocessing, feature selection, model training, hyperparameter tuning, and performance evaluation.


## Features
- Merging various tables for analysis.
- Treating missing values with a suitable approach.
- Understanding the significant insights in the data by exploratory data analysis.
- Building supervised learning models to predict the outputs.
- Comparing accuracies and other scores to get the best model for deployment.
- Data balancing techniques.

## Dataset

- Patients condition dataset



 https://www.kaggle.com/datasets/bhagyashreeaborkar/patients-conditions


- Credit card Loan dataset

 https://www.kaggle.com/code/nimapourmoradi/bank-personal-loan-classification-knn/input

## Tools and Techniques

- Python
- Numpy
- Pandas
- Matplotlib
- Seaborn
- KNN, SVM
- SMOTE
- GridSearchCV

## Analysis


#### *Patient condition Analysis


![health](https://github.com/user-attachments/assets/b44afae8-da63-4861-ba37-2b7cfd315bbb)

- Models with hyper parameter tuning using GridSerachCV  are giving good Preciison, Recall, Accuracy and F1_score.
- Most of the data features are correlated with each other.
- Best Model scores are:
**Accuracy:** 0.85 | 
**Precision:** 0.86 |
**Recall:** 0.85 |
**F1-Score:** 0.85


#### *Credit Card Loan Analysis

![supervised](https://github.com/user-attachments/assets/48a67840-0b4e-4e27-a4b2-200443ac7282)

- This dataset has class imbalance in the target variable.
- After applying SMOTE, SVM model's Accuracy increased.
- Best Model scores are:
**Accuracy:** 0.94 | 
**Precision:** 0.9 |
**Recall:** 0.94 |
**F1-Score:** 0.94 





