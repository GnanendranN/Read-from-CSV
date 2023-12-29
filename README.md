# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_CSV method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Display the result.
## PROGRAM:
Developed by: Gnanendran N
RegisterNumber: 23006661
To write a python program for reading content from a CSV file.
import pandas as pd
df = pd.read_csv('data.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
## OUTPUT:
![csvoutput](https://github.com/GnanendranN/Read-from-CSV/assets/138955207/249951d7-8117-4235-9f81-64f0dd7dd116)

## RESULT:
Thus the program excuted successfully
