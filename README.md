# CREATING AND LOADING DATASETS IN PYTHON


##  Aim of the Study

The aim of this project is to study how datasets are **created, structured, and loaded** in Python for data analysis and processing.

This project focuses on:

* Creating datasets using lists and dictionaries
* Creating datasets using Pandas
* Loading datasets from CSV files
* Loading datasets from Excel files
* Understanding dataset structure
* Viewing and inspecting data

---

##  Introduction

In Data Science and Machine Learning, datasets play a very important role.
A dataset is a structured collection of data that can be analyzed and processed.

Python provides powerful libraries to create and load datasets easily.
The most commonly used library is **Pandas**, which helps in handling structured data efficiently.

Datasets can be:

* Created manually inside Python
* Imported from CSV files
* Imported from Excel files
* Loaded from online sources

Understanding how to create and load datasets is the first step toward data analysis.

---

##  Study of Creating and Loading Datasets (Instructions)

* Import required libraries
* Create dataset using lists
* Create dataset using dictionary
* Convert data into DataFrame
* Load dataset from CSV file
* Load dataset from Excel file
* View dataset using head() and tail()
* Check dataset information
* Understand rows and columns

---


#  THEORY (Creating and Loading Datasets in Python)

---

## Importing Required Library

To work with datasets efficiently, we import the Pandas library.

```python
import pandas as pd
```

Here, `pd` is used as an alias for convenience.

---

## Creating Dataset Using Lists

A simple dataset can be created using Python lists.

```python
names = ["A", "B", "C"]
marks = [85, 90, 88]
```

Lists store data in ordered form.

---

## Creating Dataset Using Dictionary

A dictionary stores data in key-value format.

```python
data = {
    "Name": ["A", "B", "C"],
    "Marks": [85, 90, 88]
}
```

Keys represent column names, and values represent column data.

---

## Creating DataFrame

The dataset is converted into a structured table using DataFrame.

```python
df = pd.DataFrame(data)
print(df)
```

A DataFrame:

* Is two-dimensional
* Has rows and columns
* Is similar to an Excel sheet

---

## Loading Dataset from CSV File

CSV (Comma Separated Values) is the most common dataset format.

```python
df = pd.read_csv("file.csv")
```

Important functions:

* `df.head()` → Displays first 5 rows
* `df.tail()` → Displays last 5 rows
* `df.info()` → Shows dataset information
* `df.shape` → Shows number of rows and columns

---

## Loading Dataset from Excel File

Excel files can also be loaded using:

```python
df = pd.read_excel("file.xlsx")
```

This requires the `openpyxl` library.

---

## Understanding Dataset Structure

Key components of a dataset:

* Rows → Individual records
* Columns → Features or attributes
* Index → Row numbering
* Data Types → int, float, object, etc.

Checking data types:

```python
df.dtypes
```

---

## Viewing and Inspecting Data

To understand dataset content:

```python
df.head()
df.tail()
df.describe()
df.columns
```

These functions help in analyzing the structure before performing operations.

---

# Advantages of Creating and Loading Datasets in Python

* Easy to create structured data
* Supports multiple file formats
* Efficient data handling
* Useful for Data Analysis and Machine Learning
* Saves time compared to manual data entry

---

#  Disadvantages

* Large datasets consume more memory
* File format compatibility issues may occur
* Requires proper installation of libraries

---

#  Tools Used

* Python Interpreter
* Google Colab / Jupyter Notebook
* Pandas Library
* CSV and Excel Files

---

#  Applications

* Data Analysis
* Machine Learning Projects
* Research Work
* Business Analytics
* Academic Projects

---

#  Conclusion

Creating and loading datasets is a fundamental step in data analysis using Python.

Through this study, we learned:

* How to create datasets using lists and dictionaries
* How to convert data into DataFrame
* How to load datasets from CSV and Excel files
* How to inspect dataset structure
* How to understand rows, columns, and data types
