Daily Diary – Day 23

Date: 25th July 2025

Topics Covered:

Cross-Validation

K-Means Clustering

Handling Categorical Data

What I Did Today:
Today was a productive day as I explored three key concepts that are essential in machine learning and data preprocessing: cross-validation, K-Means clustering, and how to handle categorical data effectively in ML workflows.

Part 1: Cross-Validation
What I Learned:
Cross-validation is a model validation technique used to evaluate how well a model generalizes to unseen data.

I specifically learned about K-Fold Cross-Validation, where the dataset is split into k subsets, and the model is trained and validated k times — each time using a different fold as the validation set.

Why It's Useful:
Helps reduce overfitting and gives a more accurate measure of model performance.

Ensures the model performs consistently across different parts of the data.

Observations:
Cross-validation is better than using a single train-test split, especially for small datasets.

It can be combined with Grid Search for more robust hyperparameter tuning.

Part 2: K-Means Clustering
What I Learned:
K-Means is an unsupervised learning algorithm used for clustering — grouping similar data points together.

It works by initializing k centroids and assigning each data point to the nearest one, then recalculating centroids until convergence.

Use Cases:
Customer segmentation

Document classification

Image compression

Key Concepts:
Choosing the right number of clusters (k) using the elbow method

Understanding how K-Means works internally (initialization, iteration, convergence)

Observations:
K-Means works well with numerical data; categorical data must be encoded before applying the algorithm.

Feature scaling (e.g., StandardScaler) helps improve clustering performance.

Part 3: Categorical Data Handling
What I Learned:
Machine learning models require numerical input, so categorical features must be converted.

Common methods:

One-Hot Encoding – Creates binary columns for each category (suitable for nominal data)

Label Encoding – Assigns numeric labels to categories (better for ordinal data)

Observations:
One-hot encoding increases dimensionality — must be used carefully with high-cardinality features.

Choosing the correct encoding method depends on the nature of the categorical variable (nominal vs. ordinal).

Tools & Libraries Used:
Scikit-learn – For cross-validation, K-Means, encoding, and evaluation

Pandas / NumPy – For data handling and preparation

Matplotlib / Seaborn – For visualizing clusters and evaluation results

