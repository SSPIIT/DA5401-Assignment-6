Assignment 6 – Data Analytics (DA5401)

Author: Swara Sunil Patil
Roll No: MM22B045

Overview
This notebook focuses on handling missing data using different imputation strategies and evaluating their impact on model performance. The task uses the UCI Credit Card Default dataset and demonstrates both simple and regression-based methods for imputation.

Contents

1. Loading and cleaning the dataset (removal of the ID column)
2. Introducing missing values artificially in specific columns (AGE, BILL_AMT1, PAY_AMT1) to simulate missing-at-random (MAR) data
3. Applying four imputation strategies:

   * Median Imputation
   * Linear Regression Imputation
   * KNN Regression Imputation
   * Listwise Deletion
4. Evaluating the impact of each imputation method on classification performance using Logistic Regression
5. Comparing and analyzing results

How to Run

1. Open the notebook in Jupyter Notebook or Google Colab.
2. Run each cell in sequence from start to end.
3. Review outputs, visualizations, and model performance for each imputation strategy.

Results
The notebook concludes with a comparison of how different imputation methods affect the predictive accuracy of a Logistic Regression model, highlighting trade-offs between simplicity and model fidelity.
