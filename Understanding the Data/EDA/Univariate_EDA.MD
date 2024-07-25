# Univariate EDA for Categorical columns:

1.  **COUNTPLOT --> seaborn library**
	  Provides frequencies for each column
```
sns.countplot(df['col_name'])
df['col_name'].value_counts()  # provides numbers
```

2. **PIE CHART -->**
	Helps in determining percentage
```
df['col_name'].value_counts().plot(kind='pie, autopct='%.2f')
```

---

# Univariate EDA for Numerical columns:

**Numerical columns have continuous values i.e. they cannot be divided into groups like categorical columns.**
1. **HISTOGRAM**
   - It helps in converting numerical columns in categorical with the help of bins.
```
plt.hist(df['col_name'], bins=5)   
```

2. **DISTPLOT --> seaborn library **
   - An Update for histogram.
   - Tells of data is skewed or not
```
sns.distplot(df['col_name'])
```

3. **BOXPLOT --> seaborn library **
   - Used when there are outliers/noise in data set.
   - Provides 5 number summary
   - includes IQR, median, min, max etc.
```
sns.boxplot(df['col_name'])
```
