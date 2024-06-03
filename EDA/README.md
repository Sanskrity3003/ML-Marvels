# Exploratory Data Analysis (EDA)

Welcome to the Exploratory Data Analysis (EDA) repository. This guide will walk you through the tools and techniques used in EDA, focusing on both univariate and bivariate analysis.

## Table of Contents
- [Univariate Analysis](#univariate-analysis)
  - [Categorical Data](#categorical-data)
  - [Numerical Data](#numerical-data)
- [Bivariate Analysis](#bivariate-analysis)
  - [Numerical - Numerical](#numerical---numerical)
  - [Categorical - Categorical](#categorical---categorical)
  - [Numerical - Categorical](#numerical---categorical)

---

## Univariate Analysis

Univariate analysis involves the analysis of a single variable. In a dataset with multiple columns, each column can be considered as a variable, and its analysis is known as univariate analysis.

### Types of Data
Data in columns can generally be categorized into two types:

| Numerical Data     | Categorical Data               |
| ------------------ | ------------------------------ |
| age, marks, salary | name, country, state, gender   |

The first step of univariate analysis is to differentiate the data into these two categories and then proceed with appropriate plotting.

### Categorical Data
For categorical data, use the following plots:
- **Count Plot:** Useful for counting the frequency of each category.
- **Pie Chart:** Provides a visual representation of the distribution of categories. Use `autopct='%.2f%%'` to display percentages and values.

### Numerical Data
For numerical data, use the following plots:
- **Histogram:** Helps understand the distribution of data by creating ranges (bins).
- **Distplot:** An improvement over histograms, providing the probability of occurrence of a number (Probability Density Function - PDF).
- **Boxplot:** Useful for identifying outliers and understanding the spread and skewness of data.

---

## Bivariate Analysis

Bivariate analysis involves the analysis of two variables simultaneously. The combinations of data can be:

- Numerical - Numerical
- Categorical - Categorical
- Numerical - Categorical

### Numerical - Numerical
- Scatter Plot
- Line Plot
- Correlation Matrix

### Categorical - Categorical
- Cross-tabulation
- Stacked Bar Plot
- Heatmap

### Numerical - Categorical
- Boxplot
- Violin Plot
- Bar Plot

---

## Repository Structure

This repository contains scripts and examples demonstrating these techniques. Navigate through the folders to find specific analyses and visualizations.

---

## How to Use

Clone this repository to your local machine:
```bash
git clone https://github.com/your-username/your-repository.git

```


## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT](https://choosealicense.com/licenses/mit/) License


---

Thank you for exploring this repository! If you have any questions or feedback, please feel free to reach out.
