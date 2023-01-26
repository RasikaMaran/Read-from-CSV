# Read-from-CSV

## AIM:
To read and proccess the csv file

## ALGORITHM:
### Step 1:
import pandas as pd
### Step 2:
open the file in read mode
### Step 3:
print the first 9 and the tail
### Step 4:
print the rows
### Step 5:
print the columns

## PROGRAM:
```python
#developed by: Rasika.M
#reference no: 22005459
import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```

## OUTPUT:
![output](exp.png)

## RESULT:
hence the programe is executed successfully!
