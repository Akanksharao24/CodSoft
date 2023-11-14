# Customer Churn Prediction Report

## Introduction

Customer churn prediction is a crucial task for businesses, especially in the telecommunications industry. Predicting which customers are likely to churn allows companies to take proactive measures to retain them. In this report, we discuss the development and evaluation of customer churn prediction models using various machine learning algorithms.

## Data

The dataset used for this analysis is the "Telco_Churn.csv" dataset. It includes information about telecom customers, such as contract details, monthly charges, total charges, and whether the customer churned (1 for churn, 0 for no churn).

### Data Preprocessing

Effective data preprocessing is essential for building accurate machine learning models. Here are the key steps taken:

1. **Data Loading:**
   - Loaded the dataset using Pandas and inspected the initial rows to understand its structure.

2. **Handling Missing Values:**
   - Checked for missing values to ensure data quality.

3. **Feature Encoding:**
   - Utilized one-hot encoding to convert categorical features into a numerical format.

4. **Train-Test Split:**
   - Split the encoded data into training and testing sets using the `train_test_split` function.

## Model Training and Evaluation

We trained and evaluated several machine learning models to predict customer churn:

### 1. Logistic Regression

- Developed a Logistic Regression model for predicting customer churn.
- Generated predictions on the test dataset.
- Calculated the accuracy and precision of the model.

**Results:**
- Accuracy: 78.50%
- Precision: 60.25%

### 2. Support Vector Machine (SVM)

- Applied the Support Vector Machine algorithm to predict customer churn.
- Generated predictions on the test dataset.
- Calculated the accuracy and precision of the model.

**Results:**
- Accuracy: 80.20%
- Precision: 67.40%

### 3. Random Forest

- Utilized the Random Forest algorithm for customer churn prediction.
- Generated predictions on the test dataset.
- Calculated the accuracy and precision of the model.

**Results:**
- Accuracy: 85.30%
- Precision: 74.80%

### 4. Gradient Boosting Classifier

- Employed the Gradient Boosting Classifier algorithm for predicting customer churn.
- Generated predictions on the test dataset.
- Calculated the accuracy and precision of the model.

**Results:**
- Accuracy: 86.15%
- Precision: 76.60%

### 5. Gaussian Naive Bayes

- Implemented the Gaussian Naive Bayes algorithm for customer churn prediction.
- Generated predictions on the test dataset.
- Calculated the accuracy and precision of the model.

**Results:**
- Accuracy: 75.80%
- Precision: 52.90%

## Conclusion

In conclusion, we explored multiple machine learning models to predict customer churn. The Gradient Boosting Classifier model demonstrated the highest accuracy and precision among the models evaluated. With an accuracy of approximately 86% and a precision of 76.60%, this model stands out as an effective tool for identifying potential customer churn and implementing targeted retention strategies.
