# Data_Cleaning.python



## Introduction
This project demonstrates the use of the Pandas library for data cleaning, handling missing values, and detecting outliers in a dataset. It covers various techniques and methods for data preprocessing, including imputation, outlier removal using Inter Quartile Range (IQR), direct method, and Z Score.

## Functions and Methods Used
1. **Pandas Functions:**
   - `pd.read_csv()`: Reads a CSV file into a DataFrame.
   - `DataFrame.head()`: Displays the first few rows of the DataFrame.
   - `DataFrame.shape`: Returns the dimensions of the DataFrame.
   - `DataFrame.isnull()`: Checks for missing values.
   - `DataFrame.dropna()`: Drops rows with missing values.
   - `DataFrame.fillna()`: Fills missing values with specified values.
   - `DataFrame.select_dtypes()`: Selects columns based on data types.
   - `DataFrame.mode()`: Calculates the mode of each column.
   
2. **Data Visualization:**
   - `seaborn.heatmap()`: Creates a heatmap to visualize missing values.
   - `seaborn.boxplot()`: Creates a boxplot to visualize outliers.
   - `seaborn.displot()`: Creates a distribution plot.
   - `matplotlib.pyplot.show()`: Displays plots.

3. **Data Preprocessing:**
   - **Outlier Detection:**
     - Inter Quartile Range (IQR) Method
     - Direct Method
     - Z Score Method
   - **Imputation:**
     - SimpleImputer for filling missing numerical values.
     - LabelEncoder for encoding categorical variables.

## Project Name Suggestion
**DataCleanOut**: A professional project name that reflects the core functionality of the program, which is cleaning and preprocessing data while detecting and handling outliers.

---

This README file provides an overview of the code and its functionality, making it a useful reference for users who want to understand data cleaning and outlier detection techniques using the Pandas library.
