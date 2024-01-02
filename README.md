# Read-from-CSV

## AIM:
To write a python program for read a file from csv.
## ALGORITHM:
### Step 1:
The script imports the pandas library with the alias pd using the statement import pandas as pd.
### Step 2:
It uses the pd.read_csv() function to read the contents of a CSV file named 'data.csv.txt' and stores the resulting DataFrame in the variable df.
### Step 3:
The script prints the first 10 rows of the DataFrame using the head(10) method and the print(df.head(10)) statement.
### Step 4:
It prints the last 5 rows of the DataFrame using the tail(5) method and the print(df.tail(5)) statement.
### Step 5:
The script calculates and prints the number of rows in the DataFrame using the len(df.axes[0]) expression and the print("Number of rows :", len(df.axes[0])) statement.
### Step 6:
Similarly, it calculates and prints the number of columns in the DataFrame using the len(df.axes[1]) expression and the print("Number of columns :", len(df.axes[1])) statement.
## PROGRAM:
```
Developed By : ARCHANA.T
Register Number:21223240013

import pandas as pd
df=pd.read_csv('data.csv.txt')
print(df.head(10))
print(df.tail(5))
print("Number of rows :",len(df.axes[0]))
print("Number of columns :",len(df.axes[1]))
```
## OUTPUT:
![csv](https://github.com/ARCHANAT1305/Read-from-CSV/assets/145975189/d423bec4-cdae-4e2d-850c-9c6807365b5f)

## RESULT:
Thus the program executed successfully.
