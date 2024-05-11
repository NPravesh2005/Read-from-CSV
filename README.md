# Read-from-CSV

## AIM: 

To write a program to read from CSV file

## ALGORITHM:
## Step 1:
Load the CSV into a DataFrame.
## Step 2:
Print the number of contents to be displayed using df.head().
## Step 3:
The number of rows returned is defined in Pandas option settings.
## Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
## Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:

```python
#To write a python program for reading content from a CSV file.
#Developed by: PRAVESH.N
#Register Number: 212223230154

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```

## OUTPUT:

![12th expt](https://github.com/NPravesh2005/Read-from-CSV/assets/164477756/4b91697b-8423-49da-863f-e7d69fbf1f35)


## RESULT:

Thus the program is written to read the csv file.
