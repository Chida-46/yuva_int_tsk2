# Exploratory Data Analysis and Visualization – Titanic Dataset

## 1. Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic passenger dataset using Python. The main objective is to understand the dataset, clean missing data, calculate descriptive statistics, identify patterns, and visualize factors associated with passenger survival.

## 2. Objectives

- Understand the structure and characteristics of the dataset.
- Identify and handle missing values.
- Check for duplicate records and potential outliers.
- Calculate descriptive statistics.
- Analyze survival patterns by passenger sex and class.
- Create visualizations to communicate findings.
- Summarize the results and conclusions.

## 3. Dataset

The Titanic dataset contains information about passengers aboard the Titanic, including passenger class, sex, age, fare, family relationships, embarkation port, and survival status.

**Dataset source:**  
https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv

## 4. Tools and Technologies

- **Python** – Programming language
- **Pandas** – Data loading, cleaning, and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical charts
- **Google Colab / Jupyter Notebook** – Coding environment

## 5. Data Cleaning and Preparation

The following data preparation steps were performed:

1. Loaded the Titanic dataset into a Pandas DataFrame.
2. Inspected the dataset using `head()`, `info()`, `shape`, and `describe()`.
3. Checked the number of missing values in each column.
4. Checked for duplicate records.
5. Selected relevant columns for analysis.
6. Filled missing age values using the median age.
7. Filled missing embarkation port values using the most frequent value.
8. Excluded columns with substantial missing data or redundant information where appropriate.

These steps prepared the data for exploratory analysis and visualization.

## 6. Exploratory Data Analysis

The analysis included:

- Summary statistics for numerical variables.
- Counts of passengers who survived and did not survive.
- Survival rate comparisons by sex.
- Survival rate comparisons by passenger class.
- Distribution of passenger ages.
- Fare distribution and potential outlier inspection.
- Correlation analysis among selected numerical variables.
- Survival rate comparisons across passenger class and sex.

## 7. Visualizations

The project includes the following charts, where generated:

1. Survival Count Plot
2. Survival by Sex
3. Survival Rate by Passenger Class
4. Passenger Age Distribution
5. Fare Distribution and Outlier Analysis
6. Correlation Heatmap
7. Survival Rate by Passenger Class and Sex

The charts help identify patterns and communicate the results of the analysis.

## 8. Key Findings

The analysis explores whether survival outcomes differed by sex and passenger class, how passenger ages and fares were distributed, and whether relationships existed among selected numerical variables.

The exact findings should be based on the calculated statistics and generated charts. Associations observed in this dataset do not necessarily establish causation.

## 9. Conclusion

This project demonstrates how Exploratory Data Analysis can be used to understand a real-world dataset. Data inspection, missing-value treatment, descriptive statistics, and visualizations helped reveal patterns in Titanic passenger information and survival outcomes.

The project also provided practical experience with Python data analysis libraries and communicating results through charts.

## 10. How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Install the required libraries if they are not already available.
3. Run the notebook cells in order.
4. Load the Titanic dataset from the source URL.
5. Execute the data cleaning and analysis steps.
6. Generate and save the visualizations.
7. Review the charts and use the actual results in the final report.

## 11. References

- Titanic dataset: https://raw.githubusercontent.com/mwaskom/seaborn-data/master/titanic.csv
- Pandas documentation: https://pandas.pydata.org/docs/
- Matplotlib documentation: https://matplotlib.org/stable/
- Seaborn documentation: https://seaborn.pydata.org/

## Author
Chidananda M
