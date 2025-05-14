# BlinkIT Grocery Data Analysis

This repository contains a comprehensive data analysis project on BlinkIT's grocery sales dataset. The project covers data cleaning, exploratory data analysis (EDA), and data visualization using Python.

## Dataset
The dataset includes details such as:
- Item attributes (fat content, type, visibility, weight)
- Outlet attributes (location type, size, establishment year, type)
- Sales and rating data

> **Total Records**: 8,523 rows  
> **File Used**: `BlinkIT Grocery Data.xlsx` (loaded via pandas)

## Data Cleaning
- Checked and confirmed no duplicate rows.
- Identified missing values in the `Item Weight` column and filled them using the column's **mean**.
- Standardized categorical values in `Item Fat Content` (e.g., `'low fat'`, `'LF'`, and `'reg'` were cleaned to `'Low Fat'` and `'Regular'`).

## Exploratory Data Analysis (EDA)

### Summary Statistics
- Calculated mean, standard deviation, min, max, and percentiles for numeric columns.
- Example: Average Sales = 140.99, Average Rating = 3.96

### Visualizations
- **Line Chart**: Total sales trend over the years (based on Outlet Establishment Year)
- **Bar Chart**: Sales across different Item Types
- **Pie Charts**:
  - Sales by Item Fat Content
  - Sales by Outlet Size
  - Sales by Outlet Location Type
- **Column Charts**: Sales comparison across Outlet Location Type and Outlet Size
- **Clustered Bar Chart**: Sales segmented by Outlet Location Type and Item Fat Content
- **Histogram**: Distribution of sales values

## Tools Used
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
