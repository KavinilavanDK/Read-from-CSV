#EX.NO :12 Read-from-CSV

## AIM: 
To write a python program for reading csv file content

## ALGORITHM:
#### Step 1:
Load the CSV into a DataFrame.

#### Step 2:
Print the number of contents to be displayed using df.head().

#### Step 3:
The number of rows returned is defined in Pandas option settings.

#### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

#### SStep 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
To write a python program for reading content from a CSV file.
Developed by:KAVI NILAVAN DK
Register Number: 212223230103
import pandas as pd
df = pd.read_csv('salary.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

## OUTPUT:
![ex 12](https://github.com/user-attachments/assets/ebe5668f-f3f6-4f63-b66f-0e4b29d5b0df)

## RESULT:
Thus the program is written to read the csv file
