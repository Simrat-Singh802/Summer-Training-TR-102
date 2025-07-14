Daily Diary – Day 14
  
Date: 14th July 2025

Topic Covered: Introduction to EDA (Exploratory Data Analysis)

What I Did Today:
Today, I officially started learning EDA – Exploratory Data Analysis, one of the most important steps in any data science or machine learning project. EDA helps to understand the structure, quality, patterns, and
relationships within a dataset before applying any machine learning models.

I began by understanding the goals and importance of EDA, which include:

Discovering patterns, trends, and anomalies in the data

Identifying missing or duplicate values

Understanding data types and distributions

Preparing data for modeling

Key Steps I Practiced Today:
Loading the dataset using pandas.read_csv()

Using df.head(), df.tail(), df.info(), and df.describe() to get an overview of the data

Identifying missing values using df.isnull().sum()

Checking the shape and column names of the dataset

Understanding the types of columns: categorical, numerical, and boolean

Sorting and filtering data to detect any inconsistencies

I used a sample dataset (like Titanic or weather data) to apply all the above steps and tried to answer basic questions like:

How many missing values are there in each column?

What is the distribution of numerical columns?

Are there any duplicate rows?

What are the most common values in categorical columns?

Observations:
EDA is more than just printing data – it's about asking questions and looking for insights.

Even basic functions like .value_counts() or .groupby() can reveal useful information.

Handling missing data is an essential part of preparing for machine learning models.

Libraries Used:
Pandas – For data loading and manipulation

NumPy – For basic numerical operations

Seaborn & Matplotlib – For initial visual insights (like plotting distributions and counts)
