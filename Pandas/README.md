## **Pandas**

Pandas is an open-source Python library used for data manipulation, analysis and cleaning. It provides fast and flexible tools to work with tabular data, similar to spreadsheets or SQL tables.

## **Data Structures in Pandas**\
Pandas provides two data structures for manipulating data which are as follows:

**1. Pandas Series**\
A Pandas Series is a one-dimensional labeled array capable of holding data of any type. It can be created from Python lists, NumPy arrays, dictionaries, scalar values or data loaded from external sources such as CSV files, Excel files and databases. The labels associated with a Series are called its index.

**Example**

```
import pandas as pd
import numpy as np

data = np.array(['a', 'b', 'c', 'd', 'e', 'f'])
s = pd.Series(data)

print("Pandas Series:")
print(s)

```

**2. Pandas DataFrame**\
Pandas DataFrame is a two-dimensional data structure with labeled axes (rows and columns). It is created by loading the datasets from existing storage which can be a SQL database, a CSV file or an Excel file. It can be created from lists, dictionaries, a list of dictionaries etc.

**Example**

```
import pandas as pd

df = pd.DataFrame()
print(df)

s = ['apple', 'banana', 'cherry', 'mango']
df = pd.DataFrame(s)
print(df)
```
