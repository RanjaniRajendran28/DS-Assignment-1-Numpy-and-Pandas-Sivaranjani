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
Amount
Tasks Performed

Data Exploration

Created a DataFrame named transactions.
Displayed the complete DataFrame.
Retrieved the first five and last five records.
Inspected shape, column names, and data types.
Displayed selected columns.
Retrieved the last three columns using iloc.

Data Analysis

Filtered transactions where Region is North and Amount is greater than 200.
Calculated product category counts using value_counts().
Identified unique regions using unique().
Grouped transactions by Region.
Calculated the average transaction amount for each region.

Data Manipulation

Updated the Amount of TransactionID 102 to 165.
Added a Discount column representing 10% of Amount.
Removed the row with TransactionID 109.
Deleted the Discount column.
Pandas Functions and Methods
Function / Method	Purpose
pd.DataFrame()	Creates a DataFrame
head()	Displays first five rows
tail()	Displays last five rows
shape	Returns dimensions
columns	Returns column names
dtypes	Displays data types
info()	Displays DataFrame information
iloc[]	Selects data by position
loc[]	Selects data by labels or conditions
value_counts()	Counts occurrences
unique()	Finds unique values
groupby()	Groups data
mean()	Calculates average
drop()	Deletes rows or columns
⚙️ Installation and Setup
Step 1: Install Python

Download and install Python from:

https://www.python.org/downloads/

Step 2: Install Required Libraries

Open your terminal or command prompt and execute:

bash
pip install numpy pandas jupyter

Step 3: Clone the Repository
bash
git clone <your-repository-url>

Step 4: Navigate to the Project Folder
bash
cd Python-Data-Analysis

Step 5: Launch Jupyter Notebook
bash
jupyter notebook


Open the required notebook and execute the cells.

Alternatively, you can run the notebooks using Google Colab.

📚 Key Learnings

Through these exercises, I gained practical experience in:

Numerical computing with NumPy.
Creating and manipulating arrays.
Understanding Series and DataFrame structures.
Data selection and indexing.
Boolean filtering and conditional operations.
Statistical calculations.
Grouping and aggregating datasets.
Adding, updating, and deleting data.
🚀 Conclusion

This project provides hands-on experience with the fundamental concepts of Python data analysis using NumPy and Pandas.

These concepts form the foundation for further learning in data science, data analytics, and machine learning.



GitHub: Your GitHub Profile

⭐ If you find this project useful, consider giving the repository a star!
