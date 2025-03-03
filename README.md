# Machine Learning Wine Quality Classification

## Introduction
The field of machine learning aims to enable computers to learn from data and make decisions or predictions without explicit instructions. One of the most common tasks in machine learning is classification, where we predict a label for an input based on its features.

In this project, we will train, evaluate, and compare the performance of different classifiers in predicting the quality of wine using the Wine Quality dataset. Our primary goal is to use various classifiers for predicting wine quality and identify the most accurate approach. First, we combine red and white wine datasets to create one dataset, then perform the required preprocessing steps, and train four classifiers: 
1. Support Vector Machine (SVM)
2. XGBoost
3. Random Forest
4. Multilayer Perceptron (MLP)

We analyze the accuracy, F1-Score, and ROC/AUC metrics of these classifiers and identify the most effective model for wine quality detection. Finally, we compare their performance to determine the best classifier for identifying wine quality.

## Prerequisites
- Python 3.x
- scikit-learn
- XGBoost
- pandas
- numpy
- matplotlib
- seaborn
- Jupyter Notebook

## Data Preprocessing
1. Load the combined Wine Quality dataset.
2. Perform necessary preprocessing steps such as handling missing values, normalizing data, and encoding categorical variables.

## Model Training and Evaluation
1. Train the classifiers (SVM, XGBoost, Random Forest, MLP) on the preprocessed dataset.
2. Evaluate the performance of each classifier using metrics such as accuracy, F1-Score, and ROC/AUC.

## Results
- The final results will highlight the performance of each classifier and identify the best model for wine quality detection.
