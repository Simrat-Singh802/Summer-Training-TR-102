Daily Diary – Day 15

Date: 15th July 2025

Topic Covered: In-depth Study of Exploratory Data Analysis (EDA)

What I Did Today:
Today, I continued my journey into EDA by studying more advanced and practical techniques used in data preprocessing and analysis. I focused on understanding how to identify key statistics like minimum and 
maximum values of features, and also learned about encoding categorical data using one of the most common methods — One-Hot Encoding.

Topics Covered in Detail:
1. Descriptive Statistics:
Used df.min() and df.max() to find the lowest and highest values in numerical columns.

Understood how min-max analysis helps detect outliers or abnormal values in data.

Compared the range of features and identified which columns had extreme values.

Practiced using df.describe() to get summary statistics like mean, std, min, 25%, 50%, 75%, and max.

2. One-Hot Encoding:
Learned that many machine learning models cannot directly handle categorical (string) data.

Practiced using pd.get_dummies() to convert categorical variables into binary columns (one-hot vectors).

Understood the difference between label encoding and one-hot encoding, and when to use which.

Applied one-hot encoding on features like Sex, Embarked, and Pclass in the Titanic dataset.

Observed how new columns are created for each category and how it helps in model compatibility.

3. Real Dataset Practice:
Worked with datasets such as Titanic and others to apply these techniques.

Checked missing values and filled or encoded them when necessary.

Combined basic EDA with preprocessing to prepare data for modeling.

Tools & Libraries Used:
Pandas – For statistical summaries and encoding

NumPy – For numerical operations

Seaborn/Matplotlib – For optional visual checks (e.g., visualizing value ranges)

Observations:
Knowing the min and max helps in understanding the scale and spread of data.

One-hot encoding increases dimensionality, so it's important to use carefully, especially with features having many categories.

Encoding is a must before feeding data into most machine learning models.
