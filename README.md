# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Code :

```
NAME : Lathika Sunder
REGISTER NO: 212221230054 
```
```
import pandas as pd
df = pd.read_csv("SAMPLEIDS.csv")
print(df)
df.head(5)
df.describe()
df.info()
df.tail()
df.shape
df.isnull().sum()
df.fillna(value=10)
df.fillna(method='ffill')

```

# Output
### 1. Read and display DataFrame

```
import pandas as pd
df = pd.read_csv("SAMPLEIDS.csv")
print(df)
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/98150305-89b4-4f9d-8f8d-e94269d8e8e4)
### 2. Display head

```
df.head(5)
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/ad2e1d6f-280e-417a-9e48-4e6df855a350)
### 3. Describe about the dataframe  
```
df.describe()
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/b6663326-b20b-42f7-999b-db4438b79f41)
### 4. Info of datafram
```
df.info()
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/e2ed3581-ea89-4f9d-ad1b-229b5afd27ca)
### 5. Display tail
```
df.tail()
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/81a49209-a138-40a9-836e-f2571d6cf4b0)
### 6. Shape of the datafram
```
df.shape
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/1f64b9b6-76b2-4764-a3f4-e2182c1d2ffc)
### 7. Checking tha Null values
``` 
df.isnull().sum()
```
![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/2040ff5d-0744-4661-b248-fe62e996c836)
### 8. FIll the Null values
```
df.fillna(value=10)  
```
 ![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/42f9b342-5b77-479c-97c8-25d0e2d0b162)
### 9. Fill value to null values
```
df.fillna(method='ffill')
```

![image](https://github.com/Ashwinkumar-03/exno1/assets/118663725/1ad10c50-0e75-4660-95bb-e2f9f5f67d80)



# Result:
The data clearning has beeen done successfully.

