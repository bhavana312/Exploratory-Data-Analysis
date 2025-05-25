# Exploratory-Data-Analysis
# Data Preprocessing and EDA Script

This Python script performs data preprocessing, outlier detection, and exploratory data analysis (EDA) on a dataset (`dataset1.csv`). It encodes categorical variables, identifies outliers grouped by country, generates visualizations, and analyzes correlations between features.

## Features

- Loads and validates dataset file
- Identifies and encodes categorical variables using Label Encoding
- Detects outliers for each country using the IQR method
- Generates histograms for numeric features
- Performs basic EDA: data summary, info, and value counts
- Creates a correlation matrix and visual heatmap for encoded numerical data

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
