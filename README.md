# Loan-Repayment-Analysis

I’ve used a Python based implementation for this project and I’ve experimented with quite a few libraries.

Libraries like Pandas, Numpy were heavily used for literally everything done in this project.

To read in data, simply write the following commands:

import pandas as pd

df = pd.read_csv(‘path_of_file’)

df.sample(n) -> Shows ’n’ random rows present in dataset

df.info() -> Describes data types present, number of rows, number of columns, memory usage of dataset

df.describe() -> Generates descriptive statistics that summarize the central tendency, dispersion and shape of a dataset’s distribution, excluding NaN values.

df.isnull().sum() -> Shows the number of NaN values present in each column in the DataFrame.

df.column_name.value_counts() -> Shows the number of unique values present in the column in the DataFrame

In this Loan Dataset, there are 6 different DataFrames, namely credits, cycles, failures, settlements, transactions, users.

I tried finding the best way to manipulate and wrangle the data, by merging a whole lot of different columns and what worked the best for me was the groupby() and concat() method of Pandas. Using both of them I was able to visualize the dataset in many ways and reach inferences right away.
