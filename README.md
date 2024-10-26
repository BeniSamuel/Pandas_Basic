# 📊 Pandas Basics

**Description**: Welcome to the Pandas Basics repository! This repository is your go-to guide for mastering the essential concepts of the Pandas library, which is a powerful tool for data manipulation and analysis in Python. Whether you are a beginner or looking to refresh your skills, this repo has got you covered! 🚀

---

## 📚 Table of Contents

- [What is Pandas?](#what-is-pandas)
- [Why Use Pandas?](#why-use-pandas)
- [Creating DataFrames](#creating-dataframes)
- [Working with Series](#working-with-series)
- [Plotting DataFrames](#plotting-dataframes)
- [Operations on Series and DataFrames](#operations-on-series-and-dataframes)
- [Importing CSV Files](#importing-csv-files)
- [Made With ❤️ by Beni Samuel](#made-with-by-beni-samuel)

---

## 🐼 What is Pandas?

Pandas is an open-source Python library that provides high-performance, easy-to-use data structures and data analysis tools. It is built on top of NumPy and is widely used for data manipulation and analysis tasks.

---

## 🤔 Why Use Pandas?

- **Data Handling**: Simplifies data cleaning and preparation.
- **Flexibility**: Works seamlessly with various data formats.
- **Powerful Tools**: Provides rich functionalities for data analysis and manipulation.
- **Community Support**: Strong community and extensive documentation.

---

## 📑 Creating DataFrames

Learn how to create a DataFrame from scratch or using existing data sources. DataFrames are the core data structure in Pandas, allowing you to store and manipulate tabular data.

```python
import pandas as pd

# Create a DataFrame
data = {
    'Name': ['Alice', 'Bob', 'Charlie'],
    'Age': [25, 30, 35],
}
df = pd.DataFrame(data)
```

---

## 📊 Working with Series
Understand how to create and use Series, which are one-dimensional arrays in Pandas. Series are great for working with single columns of data.

```python
# Create a Series
ages = pd.Series([25, 30, 35])
```

---

## 📈 Plotting DataFrames
Discover how to visualize your data by plotting DataFrames. Visualizations help in understanding patterns and insights.

```python
import matplotlib.pyplot as plt

df.plot(x='Name', y='Age', kind='bar')
plt.show()
```

## ⚙️ Operations on Series and DataFrames
Master various operations that can be performed on Series and DataFrames, such as filtering, aggregating, and transforming data.

```python
# Filter DataFrame
filtered_df = df[df['Age'] > 30]
```

## 📥 Importing CSV Files
Learn how to import CSV files and work with them effectively. Pandas makes it easy to read and write data in CSV format.

```python
# Import a CSV file
df = pd.read_csv('data.csv')
```
## 🤝 Contribution
Contributions are welcome! If you have suggestions or improvements, feel free to submit a pull request or open an issue.

> Made with ❤️ by Beni Samuel
