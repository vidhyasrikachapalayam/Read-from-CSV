# Read-from-CSV

## AIM:
To write a python program to read data from CSV file.


## ALGORITHM:
### Step 1:
Start the python
### Step 2:
Import pandas.
### Step 3:
Mention the CSV file which is to be read.
### Step 4:
Read the contents of the CSV file using df.read function.
### Step 5:
End the program.

## PROGRAM:
Developed by: vidhyasri.k

RegisterNumber: 22008468

import pandas as pd

df = pd.read_csv("nba.csv")

print(df.head(10))

print(df.tail())

print("column", len(df.axes[0]))

print("rows", len(df.axes[1]))

## OUTPUT:
![csv](https://user-images.githubusercontent.com/119477817/215100323-47ad5415-f4f5-46d4-a3cc-73ad36d26782.png)


## RESULT:
A python program to read data from CSV files has been created successfully.
