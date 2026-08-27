# DATA-ANALYTICS-ABOUT-THE-DATASET
1. AIM

To perform data analytics on a given dataset using Python and Pandas, understand the characteristics of the dataset, identify different types of data, examine missing values, and prepare the dataset for further analysis and machine learning.

2. THEORY

Data analytics is the process of examining, cleaning, transforming, and interpreting data to obtain useful information. Python provides several libraries for data analysis, among which Pandas is one of the most commonly used libraries.

A dataset is a collection of related data arranged in rows and columns. Pandas provides a DataFrame structure to store and manipulate tabular data efficiently.

The main steps involved in analyzing a dataset are loading the dataset, understanding its structure, identifying data types, checking missing values, obtaining statistical information, and preparing the data for further analysis.

3. PROGRAM
import pandas as pd

# Load the dataset
data = pd.read_csv("dataset.csv")

# Display the dataset
print("Dataset:")
print(data)

# Display first five records
print("\nFirst five records:")
print(data.head())

# Display dataset information
print("\nDataset Information:")
data.info()

# Display shape of dataset
print("\nShape of Dataset:")
print(data.shape)

# Display column names
print("\nColumn Names:")
print(data.columns)

# Display data types
print("\nData Types:")
print(data.dtypes)

# Check missing values
print("\nMissing Values:")
print(data.isnull().sum())

# Display statistical description
print("\nStatistical Description:")
print(data.describe())

# Check duplicate rows
print("\nDuplicate Rows:")
print(data.duplicated().sum())
4. OUTPUT

The program displays the dataset, first five records, number of rows and columns, column names, data types, missing values, statistical description, and duplicate rows.

5. RESULT

Thus, the given dataset was successfully analyzed using Python and Pandas. The characteristics, data types, missing values, statistical information, and duplicate records of the dataset were identified successfully.
