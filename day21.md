Daily Diary – Day 21

Date: 23rd July 2025

Topic Covered: Decision Tree – Classification Algorithm

What I Did Today:
Today, I studied and implemented the Decision Tree algorithm, one of the most intuitive and powerful machine learning models for both classification and regression tasks. I focused on using Decision Trees for classification problems and learned how the model makes decisions based on feature values.

Key Concepts I Learned:
1. What is a Decision Tree?
A Decision Tree is a tree-like structure where:

Internal nodes represent decision points based on features

Branches represent the outcome of a decision

Leaf nodes represent the final class label (or output value)

The model splits the dataset into smaller subsets based on conditions that best separate the data, using concepts like:

Gini Impurity

Entropy

Information Gain

2. Advantages of Decision Trees:
Easy to understand and visualize

Can handle both numerical and categorical data

Doesn’t require feature scaling

Works well for small to medium datasets

3. What I Practiced:
Applied a Decision Tree to a real dataset (e.g., Titanic or Iris)

Split data into training and testing sets

Trained the model and made predictions

Visualized the decision tree structure to understand how the model is making decisions

Evaluated the model using accuracy and a confusion matrix

4. Visualization:
Explored how the model splits features step by step

Visualized the tree diagram to interpret the rules and thresholds at each split

Observations:
Decision Trees are simple to implement but can overfit on training data if not properly limited (using max_depth, min_samples_split, etc.)

Visualization helps in understanding model logic, making it ideal for explainable AI

Tree-based models are great when there is non-linear or complex data

Tools & Libraries Used:
Pandas – Data preparation

Scikit-learn – Model building and visualization

Matplotlib / Seaborn – For evaluating and plotting results

Graphviz or plot_tree() – For visualizing the tree structure

