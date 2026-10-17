# Dataset Exploration Using Pandas

## Overview
This project explores the structure and basic characteristics of a tabular dataset using Python and Pandas. It demonstrates how to inspect records, identify column types, review descriptive statistics, and check for missing values before further data analysis or modeling.

## Objectives
- Inspect the first and last records of a dataset.
- Determine the number of rows and columns.
- Review column names and data types.
- Generate descriptive statistics for numerical columns.
- Identify numerical and categorical columns.
- Check for missing values.
- Summarize key observations from the dataset.

## Tools and Technologies
- Python
- Pandas
- Jupyter Notebook / Google Colab

## Dataset
The notebook creates a sample student dataset containing 10 records and 5 columns:

| Column | Description | Data Type |
|---|---|---|
| `StudentID` | Unique identifier for each student | Numerical |
| `Name` | Student name | Categorical |
| `Gender` | Student gender | Categorical |
| `Attendance` | Attendance percentage/value | Numerical |
| `Marks` | Student marks | Numerical |

The sample dataset is included in the notebook and can be replaced with another CSV dataset if needed.

## Analysis Performed
The notebook uses the following Pandas features:

- `head()` and `tail()` to display the first and last five records.
- `shape` to retrieve the number of rows and columns.
- `columns` to list the column names.
- `info()` to inspect data types and non-null counts.
- `describe()` to summarize numerical columns.
- `select_dtypes()` to identify numerical and categorical columns.
- `isnull().sum()` to count missing values in each column.

## Key Observations
For the included sample dataset:
1. The dataset contains 10 rows and 5 columns.
2. It has 3 numerical columns and 2 categorical columns.
3. The average student mark is 76.8.
4. The highest mark is 95.
5. The lowest mark is 55.
6. No missing values are present in the sample data.

## How to Run
1. Open the notebook in Google Colab or Jupyter Notebook.
2. Run the code cells in order.
3. Review the dataset preview, structure, statistical summary, missing-value counts, and observations.
4. To analyze another dataset, replace the sample data with your own dataset and update the column names used in the analysis.

## Project Structure
```text
Dataset-Exploration/
├── Dataset_Exploration.ipynb
└── README.md
```

## Conclusion
This project demonstrates the essential first steps in dataset exploration. Understanding dataset dimensions, column types, summary statistics, and missing values helps prepare data for further cleaning, visualization, and machine learning tasks.
