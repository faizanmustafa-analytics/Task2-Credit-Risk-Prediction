# Task 2: Credit Risk Prediction

## Objective
The objective of this task is to predict whether a loan applicant is likely to default on a loan using machine learning techniques.

## Dataset
Loan Prediction Dataset (Kaggle)  
Source: https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset

## Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

## Steps Performed
1. Loaded the loan prediction dataset using pandas.
2. Checked dataset shape, columns, and basic structure.
3. Handled missing values:
   - Categorical values filled using mode.
   - Numerical values filled using median.
4. Encoded the target variable (Loan_Status).
5. Performed Exploratory Data Analysis (EDA):
   - Loan amount distribution
   - Education vs loan status
   - Applicant income analysis
6. Converted categorical features using one-hot encoding.
7. Trained a Logistic Regression model.
8. Evaluated the model using:
   - Accuracy score
   - Confusion matrix

## Model Used
- Logistic Regression

## Evaluation Metrics
- Accuracy
- Confusion Matrix

## How to Run
1. Place `loan_prediction.csv` in the same folder as the notebook.
2. Open the notebook in Jupyter.
3. Run all cells sequentially.

## Outcome
The model successfully predicts loan default status with reasonable accuracy and meets all internship task requirements.

