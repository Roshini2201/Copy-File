# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 

### Step 1:
Load the CSV into a DataFrame.

### Step 2:
Print the number of contents to be displayed using df.head().

### Step 3:
The number of rows returned is defined in Pandas option settings.

### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

### Step 5:
Increase the maximum number of rows to display the entire DataFrame

### Step 6:
End the program.

## PROGRAM:
```
To write a python program for reading content from a CSV file.
Developed by: ROSHINI S
Register Number: 212223240142

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))
```
### OUTPUT:

![329608372-8863c292-e6b0-4229-997f-80ea3da64c84](https://github.com/Roshini2201/Copy-File/assets/154105318/12e0fe04-5d4a-4a9f-9ebd-f1c5a9469d67)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
