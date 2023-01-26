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
Register no: 22009090

import pandas as pd
df = pd.read_csv("data.csv")
print(df.head(10))
print(df.tail())
print("No.of Rows:",len(df.axes[0]))
print("No.of Columns:",len(df.axes[1]))
```
## OUTPUT:
![output](./WhatsApp%20Image%202023-01-26%20at%2013.18.38.jpg)


## RESULT:
 Thus the program is writen to read the csv file.