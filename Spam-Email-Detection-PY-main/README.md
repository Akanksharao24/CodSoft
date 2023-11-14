# Spam-Email-Detection----

# Spam Email Detection Model Evaluation

In this report, we present the development and evaluation of a spam email detection model using a Multinomial Naive Bayes classifier.

## 1. Introduction

Spam emails pose a significant threat, leading to potential security risks, privacy invasion, and resource wastage. The focus of this report is on the development and evaluation of a Multinomial Naive Bayes classifier for spam email detection.

## 2. Data Exploration and Preprocessing

The dataset 'spam.csv' was explored, and preprocessing steps were implemented:

- Missing values were handled.
- Unnecessary columns (Unnamed: 2, Unnamed: 3, Unnamed: 4) were dropped.
- Duplicate entries were removed.
- Column names were clarified for better understanding.

## 3. Data Representation and Splitting

The 'message' column's text data was transformed into numerical format using CountVectorizer. The dataset was split into training and testing sets to facilitate model training and evaluation.

## 4. Model Training

A Multinomial Naive Bayes classifier was selected and trained on the training set using the fit method.

## 5. Model Evaluation

The model was evaluated on the test set, and its performance was assessed using various metrics:

- **Confusion Matrix:**
  - True Negatives: 872
  - False Positives: 13
  - False Negatives: 10
  - True Positives: 139

- **Accuracy:** Approximately 97.78%
- **Precision:** Approximately 91.45%
- **F1 Score:** Approximately 92.36%

## 6. Visualizations

Visualizations were incorporated for better presentation:

- **Class Distribution Bar Chart:**
  - Displays the distribution of 'ham' and 'spam' classes in the dataset.

- **Confusion Matrix Heatmap:**
  - Provides a clear visual representation of the model's performance.

## 7. Conclusion

In conclusion, the developed spam email detection model utilizing a Multinomial Naive Bayes classifier demonstrates high accuracy, precision, and F1 score. Visualizations enhance the communication of results, and continuous model monitoring is recommended to adapt to evolving spam email patterns.
