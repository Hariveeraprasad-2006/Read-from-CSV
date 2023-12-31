# Read-from-CSV

## AIM:TO Read the CSV form file

## ALGORITHM:
### Step 1:
first import pandas as pd
### Step 2:
Then open the csv file
### Step 3:
Use head() to print the first starting lines and tail() to read the last lines. 
### Step 4:
use  axes(0) to print coloumns and axes(1) to print rows.
### Step 5:
then run the programme
## PROGRAM:
```
#Developed By:Arikatla Hari Veera Prasad
#Register Number:212223240014
import pandas as pd
df = pd.read_csv('cars.csv')
print(df.head())
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))
```
## OUTPUT:
![Screenshot 2023-12-31 150311](https://github.com/Hariveeraprasad-2006/Read-from-CSV/assets/145049988/31fe4a43-f26b-4cba-8b67-ed06663319f5)
## RESULT:
This Python program is used to read the csv file
