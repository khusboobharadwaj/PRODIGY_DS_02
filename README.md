# Prodigy_DataScience_Task2
Titanic Dataset Analysis
Overview
This project involves data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. The goal is to identify patterns, explore relationships between variables, and uncover trends in the data. The Titanic dataset provides information on the passengers of the Titanic, including demographic information, passenger class, and survival status.

Dataset
The dataset used in this project is the Titanic dataset from Kaggle. It includes the following columns:

PassengerId: Unique identifier for each passenger
Survived: Survival status (0 = No, 1 = Yes)
Pclass: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
Name: Name of the passenger
Sex: Sex of the passenger
Age: Age of the passenger
SibSp: Number of siblings/spouses aboard the Titanic
Parch: Number of parents/children aboard the Titanic
Ticket: Ticket number
Fare: Passenger fare
Cabin: Cabin number
Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Requirements
The following Python libraries are required to run the analysis:
pandas
seaborn
matplotlib
numpy

Data Cleaning
Handling Missing Values:

Fill missing values for 'Age' with the median age.
Fill missing values for 'Embarked' with the most frequent value (mode).
Drop the 'Cabin' column due to a high number of missing values.

Converting Categorical Variables to Numerical:
Convert 'Sex' to numerical values (0 for male, 1 for female).
Convert 'Embarked' to numerical values using one-hot encoding.

Exploratory Data Analysis (EDA)
Summary Statistics
Generate summary statistics of the dataset to understand the distribution and central tendencies of the variables.
Univariate Analysis:
Visualize the distribution of individual variables:
Age: Histogram to show the distribution of passenger ages.
Pclass: Count plot to show the number of passengers in each class.
Survived: Count plot to show the number of survivors and non-survivors.

Bivariate Analysis:
Explore relationships between two variables:
Survival Rate by Pclass: Bar plot to show survival rates across different passenger classes.
Survival Rate by Sex: Bar plot to show survival rates between male and female passengers.
Age Distribution by Survival: Histogram to show age distribution across survival status.

Multivariate Analysis
Explore relationships between multiple variables:
Pairplot: Visualize relationships between 'Survived', 'Age', 'Pclass', 'Fare', and 'Sex'.
Correlation Heatmap: Heatmap to show correlations between different numerical features.

Age Group Analysis:
Create age groups (e.g., Child, Teenager, Adult, Middle-Aged, Senior) and analyze the distribution of survival within these age groups.

Identifying Patterns and Trends
Summarize key findings from the EDA:
Passengers in higher classes (1st class) had higher survival rates.
Female passengers had a significantly higher survival rate compared to male passengers.
Younger passengers, especially children, had higher chances of survival.
Visualizations of survival rates across different age groups and passenger classes.
