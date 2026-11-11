# NumPy and Pandas – Data Analysis Project

## Project Overview

This project focuses on performing data analysis using **NumPy and Pandas** in Python.

The assignment involves analyzing two weeks of temperature data using NumPy and performing structured data manipulation and analysis using Pandas Series and DataFrames.

## Objectives

- Perform numerical computations using NumPy arrays.
- Create and manipulate Pandas Series.
- Create and analyze Pandas DataFrames.
- Apply indexing, slicing, and filtering techniques.
- Perform aggregation and statistical operations.
- Understand real-world data analysis using temperature and transaction datasets.

## Technologies Used

- Python
- NumPy
- Pandas
- Google Colab / Jupyter Notebook

## Project Tasks

### 1. NumPy Array Operations

**Temperature Analysis**

- Create a 1D NumPy array for Week 1 temperature data.
- Inspect array properties such as shape, data type, and size.
- Convert Celsius temperatures into Fahrenheit.
- Calculate maximum, minimum, and mean temperatures.
- Perform array indexing and slicing.
- Create a 2D array containing temperature data for two weeks.
- Extract weekly temperatures and weekend temperatures.

### 2. Pandas Series Operations

**Student Marks Analysis**

- Create a Pandas Series with student marks and custom index labels.
- Access values using integer indexing.
- Retrieve data using `loc` and `iloc`.
- Apply Boolean masking to filter marks greater than 90.
- Update the first-ranked student's marks.
- Remove the last-ranked student's entry.
- Calculate CGPA by dividing marks by 10.

### 3. Pandas DataFrame Operations

**Transaction Data Analysis**

- Create a DataFrame containing transaction details.
- Explore data using `head()`, `tail()`, `shape`, `columns`, `dtypes`, and `info()`.
- Select specific columns.
- Retrieve the last three columns using `iloc`.
- Filter transactions based on region and amount.
- Calculate product category value counts.
- Identify unique regions.
- Group transactions by region and calculate the average amount.
- Update transaction amounts.
- Add a discount column.
- Remove a specific transaction.
- Delete the discount column.

## Dataset Details

### Temperature Dataset

Contains daily average temperatures in Celsius for two weeks.

- Week 1: 7 daily temperature values.
- Week 2: 7 daily temperature values.

### Student Marks Dataset

Contains marks of five students with custom rank-based indices.

### Transaction Dataset

Contains 10 transaction records with the following attributes:

- Transaction ID
- Product Category
- Region
- Amount

## Installation and Requirements

Install the required Python libraries:

```bash
pip install numpy pandas
```

Import the libraries:

```python
import numpy as np
import pandas as pd
```

## How to Run the Project

1. Clone or download this repository.
2. Open the Google Colab or Jupyter Notebook file.
3. Ensure NumPy and Pandas are installed.
4. Execute the notebook cells sequentially.
5. Observe the outputs for each operation.

## Learning Outcomes

Through this project, I gained practical knowledge of:

- NumPy array creation and manipulation.
- Array properties and mathematical operations.
- Indexing and slicing techniques.
- Pandas Series and DataFrame creation.
- Data selection and filtering.
- Boolean indexing.
- Data aggregation and grouping.
- Data modification and deletion.

## Conclusion

This project provides hands-on experience in using NumPy and Pandas for data analysis. It demonstrates how Python can be used to process numerical data, manipulate structured datasets, and extract meaningful insights from real-world scenarios.

---

**Project Type:** Python Data Analysis Assignment  
**Libraries:** NumPy, Pandas  
**Environment:** Google Colab / Jupyter Notebook
