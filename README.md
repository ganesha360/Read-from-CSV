# Read-from-CSV

## AIM:
To write a python program for reading csv filr content
## ALGORITHM:
### Step 1:
Load the csv into a dataframe.
### Step 2:
Print the number of contents to be displayed using df.head()
### Step 3:
The number of rows returned is defined in pandas option settings
### Step 4:
Check your system's maximum coloumn with the pd.options.max_coloumn statement.
### Step 5:
Increase the maximum nimber of rows to display the entire DataFrame
## PROGRAM:
```
Developed by: Ganesh R
Register no: 212222240029

import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/ganesha360/Read-from-CSV/assets/120884552/f1015bd4-7113-463c-8435-bea9ab7ee0a4)



## RESULT:
 Thus the program is writen to read the csv file.
