#### Below are some very basic questions that you would want to know in a given data set:

- **How Big is data?**         
``` 
df.shape 
``` 

- **How does the data look like?**  
``` 
df.head(10) 
```

- **How does the data look like?(for random set of values)**
```
df.sample(5)
```

- **What is the data type of the columns?**
 ``` 
 df.info()
  ``` 

- **To check missing values?**
 ``` 
 df.isnull().sum()
  ```

- **How does the data look mathematically?**
```
df.describe()
```

- **Are there any duplicated values?** 
```
df.duplicated.sum()
df.drop_duplicates() # to remove the duplicated values
```

- **How are the columns correlated to each other?**
--> Connected to dimentionality reduction.
--> Remove the columns that are not related
--> Ranges from -1 to 1, works on pearson correlation.
```
df.corr()['col_name']
```

