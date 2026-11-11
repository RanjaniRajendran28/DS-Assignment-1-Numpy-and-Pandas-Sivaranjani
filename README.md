# DS-Assignment-1-Numpy-and-Pandas-Sivaranjani
Python Data Analysis Using NumPy and Pandas
📌 Project Overview

This project demonstrates fundamental data manipulation and analysis techniques using NumPy and Pandas in Python.

The project covers NumPy array operations, Pandas Series, and Pandas DataFrames through practical examples involving temperature analysis, student marks, and transaction data.

🎯 Objectives
Understand NumPy arrays and their operations.
Learn how to create and manipulate Pandas Series.
Explore and analyze Pandas DataFrames.
Perform indexing, slicing, and filtering.
Apply mathematical and statistical operations.
Group and summarize data using Pandas.
🛠️ Technologies Used
Programming Language: Python
NumPy: Numerical computing and array manipulation.
Pandas: Data analysis and manipulation.
Platform: Jupyter Notebook / Google Colab
📂 Project Structure
text
Python-Data-Analysis/
│
├── NumPy_Array_Operations.ipynb
├── Pandas_Series.ipynb
├── Pandas_DataFrame.ipynb
│
└── README.md

1. NumPy Array Operations
Description

This exercise focuses on creating and manipulating one-dimensional and two-dimensional NumPy arrays using daily temperature data collected over two weeks.

Tasks Performed
Created a 1D NumPy array named temperatures_w1.
Inspected array shape, data type, and number of elements.
Converted temperatures from Celsius to Fahrenheit.
Calculated maximum, minimum, and mean temperatures.
Performed array slicing and indexing.
Created a 2D array containing temperatures for two weeks.
Extracted individual weeks and weekend temperatures.
NumPy Functions and Attributes
Function / Attribute	Purpose
np.array()	Creates a NumPy array
.shape	Returns array dimensions
.dtype	Returns data type
.size	Returns number of elements
np.max()	Finds maximum value
np.min()	Finds minimum value
np.mean()	Calculates mean
Array slicing	Extracts specific elements
2. Pandas Series
Description

This exercise demonstrates how to create and manipulate a Pandas Series using student marks and custom index labels.

Dataset
Rank	Marks
Rank1	95
Rank2	92
Rank3	89
Rank4	85
Rank5	80
Tasks Performed
Created a Pandas Series named marks.
Assigned custom indices from Rank1 to Rank5.
Accessed elements using integer indexing.
Retrieved values using loc and iloc.
Applied Boolean masking to filter marks greater than 90.
Modified the first-ranked student's mark to 100.
Removed the last-ranked student.
Calculated CGPA by dividing marks by 10.
Pandas Functions and Methods
Function / Method	Purpose
pd.Series()	Creates a Pandas Series
loc[]	Accesses elements using labels
iloc[]	Accesses elements using positions
Boolean Masking	Filters data based on conditions
drop()	Removes Series elements
Arithmetic Operations	Performs calculations on Series
3. Pandas DataFrame
Description

This exercise focuses on creating, exploring, filtering, grouping, and manipulating transaction records using a Pandas DataFrame.

Dataset

The transaction dataset contains 10 records with the following columns:

TransactionID
ProductCategory
Region
