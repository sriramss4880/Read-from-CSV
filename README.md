# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
Step 1:
Import pandas as pd.
Step 2:
Read the CSV file using read_csv method.
Step 3:
Use head and tail method to get the required contents from the file.
Step 4:
Use len() method to get the number of rows and columns
Step 5:
Print the output.
## PROGRAM:
#To write a python program for reading content from a CSV file.
#eveloped by: S.S.SRIRAM
#Register Number: 22004880

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
## OUTPUT:
![WhatsApp Image 2023-01-26 at 10 45 16](https://user-images.githubusercontent.com/120554177/214805769-02393267-cdc9-4167-bb90-463a3c6cb4fc.jpg)

## RESULT:
Thus a python program is written to read the contents of a CSV file.

