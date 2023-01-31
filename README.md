# Read-from-CSV

## AIM:
To read the csv file and bring it in the output
## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns
### Step 5:
Print the output
## PROGRAM:
```python
#Developed by:Prithviraj.V
#Register Number: 22004659

import pandas as pd
df = pd.read_csv('nba.csv')
print(df.head(10))
print(df.tail())
print("rows",len(df.axes[0]))
print("columns",len(df.axes[1]))
```
## OUTPUT:
![image](https://user-images.githubusercontent.com/121418418/215686620-5daa49cd-4748-4e00-87a6-9de0da3f9265.png)
![image](https://user-images.githubusercontent.com/121418418/215686706-22dbf87a-07e7-4939-a02a-59bcf843c3f8.png)


## RESULT:
The above data is the required result brought by reading the csv file.
