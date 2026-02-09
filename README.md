# PCA--Africa-GDP
## Formative 2 – Principal Component Analysis (PCA)
African GDP Over Time (2000–2020)
#### Project Overview

This repository contains the completed Jupyter/Colab notebook for the Formative 2 assignment in the Advanced Linear Algebra module.
The task applies Principal Component Analysis (PCA) from scratch to a real-world, African-focused dataset: Global Development Indicators (2000–2020), filtered specifically for African countries.

The goal of PCA is to reduce dimensionality while retaining the majority of variance in the dataset.
This notebook demonstrates:

Standardizing data using NumPy only (no sklearn standardizer used)

Handling missing numeric values

Computing the covariance matrix

Manually performing eigendecomposition

Selecting the optimal number of principal components

Projecting data onto lower-dimensional space

Visualizing data before and after PCA

Showing GDP trends over time for African countries

Dataset Information

**Source**: Public dataset: Global Development Indicators (2000–2020)

Includes countries from multiple regions — filtered to African countries only

##### Key variables used (numeric features):

GDP (current USD)

GDP per capita

Inflation rate

Unemployment rate

Exports

Imports

Government expenditure

National savings

Foreign direct investment

Population

Life expectancy

Preprocessing Steps

Filter dataset to include only rows where region contains Africa

Select numeric columns only

Handle missing values by replacing NaNs with column means

Standardize numeric features using NumPy operations

Exclude non-numeric columns such as:

country_name

region

income_group

year (excluded from PCA but used in the time-series visualization)

##### Dataset Requirements (✓ Met)

✔ More than 10 numeric features

✔ Contains missing values

✔ Contains non-numeric columns

✔ Real-world Africanized dataset

✔ Suitable for PCA

Note: The CSV dataset is not included here due to size and licensing.
Please download the dataset separately and upload it into your environment before running the notebook.

##### Requirements

Python 3.x

NumPy

Pandas

Matplotlib

These libraries come preinstalled in Google Colab and most Jupyter environments.

#### How to Run the Notebook

Open the notebook African_GDP_PCA_Analysis.ipynb in Google Colab or Jupyter.

If using Colab, upload the dataset or mount Google Drive:

from google.colab import drive
[drive.mount('/content/drive')](https://colab.research.google.com/drive/1E5dRptulLgvn_Bi2CDJIDivaFcoie8FP?usp=sharing)


Run all cells sequentially:

Load & inspect the dataset

Preprocess & standardize

Perform PCA using NumPy

Generate GDP vs Time plot

Visualize PCA results

##### Author
###### Nehemie ISHIMWE
Advanced Linear Algebra – Formative 2 (PCA Assignment)
African GDP Over Time — PCA Implementation from Scratch
