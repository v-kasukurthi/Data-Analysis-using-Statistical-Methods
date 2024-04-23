# Data-Analysis-using-Statistical-Methods

**Introduction**

This project aims to perform a comprehensive analysis of the Iris dataset using various statistical and machine learning techniques. The Iris dataset is a popular dataset in the field of machine learning and statistics, containing measurements of iris flowers from three different species: setosa, versicolor, and virginica.

**Code Overview**

The provided code consists of Python scripts written using popular libraries such as NumPy, Pandas, Matplotlib, Seaborn, SciPy, Statsmodels, Scikit-learn, and MLxtend. Below is a brief overview of the main sections of the code:

Data Loading and Exploration: The code begins by loading the Iris dataset from a CSV file and performing initial data exploration using Pandas. This includes checking for missing values, describing the dataset, and examining unique values in the 'Species' column.

Data Preprocessing: Various preprocessing steps are performed, such as dropping unnecessary columns ('Id'), replacing categorical labels with numerical values, and checking data distribution using Shapiro-Wilk test.

Correlation Analysis: The code calculates and visualizes the correlation matrix between all numerical variables using Seaborn's heatmap.

Nonparametric Tests: Nonparametric tests such as the Z-test and the one-way ANOVA (F-test) are conducted to compare means across different groups.

Analysis of Categorical Data: The code performs a chi-squared test of independence to analyze the relationship between two categorical variables.

Linear Regression: Linear regression analysis is performed to model the relationship between predictor variables and the target variable ('Species').

Resampling Methods: Resampling techniques such as k-fold cross-validation are utilized to evaluate model performance.

Linear Model Selection and Regularization: Techniques like Lasso and Ridge regression are employed for feature selection and regularization.

Feature Selection: Forward and backward feature selection methods are implemented using MLxtend library.

Principal Component Analysis (PCA): PCA is applied to reduce the dimensionality of the dataset and visualize the data in lower dimensions.

Multinomial Logistic Regression: Polynomial regression is used to model the relationship between predictor variables and the target variable.

**Usage**

To run the code:

Ensure that Python and the required libraries are installed.
Download the Iris dataset CSV file and update the file path in the code.
Execute the Python script in your preferred environment (e.g., Jupyter Notebook, Python IDE).

**Dependencies**

1.Python 3.x

2.NumPy

3.Pandas

4.Matplotlib

5.Seaborn

6.SciPy

7.Statsmodels

8.Scikit-learn

9.MLxtend
