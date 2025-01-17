# Prerequisites
- A copy of Anaconda / Miniconda installed on your PC
- Python 3 installed on your PC

# Administrative Details
- Google Classroom
- Graded Modules
- Support: mentor@algorit.ma or samuel@algorit.ma

# Python for Data Analytics
- List: `salary=[15, 7, 7, 10, 8]`
- Zero-based indexing
    - `salary[3]`
    - `salary[0:2]`
    - `salary[-2]`
    - `salary[0:3:2]`
    - General syntax: `[start:end:step]`

- We make python more suitable for data analysis by importing packages
    - `import pandas as pd`

- `pd.read_csv("/financial_report/sales2019.csv")`
- By default, it wouldn't know which column to use as index
    - `sales = pd.read_csv("/financial/sales2019.csv", index_col=0)`
- `sales.head()` and `sales.tail()` show the first or last 5 rows respectively
- `sales.shape` print the number of rows and columns
- When I convert something to a DataFrame, the DataFrame gain the following attributes:
    - .shape
    - data types: .dtypes
- When I convert something to a DataFrame, the DataFrame gain the following method:
    - .head()
    - .tail()
    - method can take additional parameters
    
- pd.read_csv("where_data_locates.csv", index_col)

- Naming your variables
    - Python is case-sensitive
    - Don't start with a number; Don't use dashes
    - Convention: use underscores: `weekly_stock_returns_q4`
    - Don't use a python keyword
        - `False = 10`

- pandas has two data types:
    - Series (pd.Series)
        - example: `pd.Series([100, 50, 0, 25.5])`
    - DataFrame(pd.DataFrame)
        - Method 1 example: `pd.DataFrame(my_dict)`
        - Method 2 example: `pd.read_csv()`

- For a pandas object, you can call methods and access attributes such as:
    - .dtypes
        - Categorical, Int, Float, DateTime, Object
    - .shape
    - .describe()
    - .head(), .tail()


# Agenda
630pm: Class begins
740pm: Break
810pm: End of Break
930pm: End of Class

# Resources and Extra Materials
- https://github.com/onlyphantom/dataanalysis



