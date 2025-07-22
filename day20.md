Daily Diary – Day 20

Date: 22nd July 2025

Topic Covered: Logistic Regression – Classification Algorithm

What I Did Today:
Today, I studied and implemented Logistic Regression, a fundamental classification algorithm in machine learning. Unlike Linear Regression, which predicts continuous values, Logistic Regression is used to predict categorical outcomes — for example, yes/no, true/false, or 0/1.

Key Concepts I Learned:
1. What is Logistic Regression?
Logistic Regression is a supervised learning algorithm used when the dependent variable is categorical.

It estimates the probability that a given input belongs to a particular class using the sigmoid function, which outputs values between 0 and 1.

Based on a threshold (typically 0.5), it assigns the input to class 0 or class 1.

2. Use Cases of Logistic Regression:
Predicting whether a student will pass or fail

Email spam detection

Disease diagnosis (positive or negative)

Customer churn (will leave/stay)

3. Steps I Followed:
Selected a dataset suitable for binary classification (like Titanic or a custom dataset)

Cleaned the data and selected relevant features

Split the data into training and testing sets

Trained a logistic regression model and made predictions

Evaluated the model using accuracy, confusion matrix, precision, and recall

4. Model Evaluation Metrics:
Accuracy – Overall correctness

Confusion Matrix – Breakdown of correct and incorrect predictions

Precision & Recall – Important when dealing with imbalanced datasets

F1 Score – Harmonic mean of precision and recall

Observations:
Logistic Regression is simple yet powerful for binary classification problems.

Choosing the right features significantly improves prediction accuracy.

Evaluation metrics help in understanding not just if the model is correct, but how and where it is making errors.

Tools & Libraries Used:
Pandas – For data handling

Scikit-learn – For training and evaluating the model

Seaborn/Matplotlib – For visualizing the confusion matrix and classification results

