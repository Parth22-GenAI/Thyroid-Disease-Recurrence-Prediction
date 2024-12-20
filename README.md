
# Thyroid Disease Recurrence Prediction Using Machine Learning
This project predicts thyroid disease recurrence using various machine learning algorithms, with a focus on comparing model performance.

# Overview
We applied the following models to a dataset with 13 clinical features:

-Logistic Regression
-Naive Bayes (Gaussian)
-Support Vector Machine (SVM)
-K-Nearest Neighbors (KNN)
-SVM achieved the highest accuracy (89.4%) in predicting thyroid disease recurrence.

# Key Steps
Data Preprocessing: Handled missing values, one-hot encoding, and standardization.
Model Tuning: GridSearchCV was used for hyperparameter tuning.
Evaluation: Accuracy, confusion matrices, and classification reports were used to assess model performance.

## Results

| Model                | Accuracy  |
|----------------------|-----------|
| Logistic Regression   | 85.3%     |
| Naive Bayes (Gaussian)| 82.7%     |
| SVM (Best Model)      | 89.4%     |
| K-Nearest Neighbors   | 84.5%     |

# Conclusion
The SVM model provides the best performance for predicting thyroid disease recurrence. Further improvements could include trying advanced models and feature selection techniques.
