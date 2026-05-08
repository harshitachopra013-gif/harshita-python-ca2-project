# harshita-python-ca2-project
harshita-python-ca2-project
# Python CA2 Project – Banking Data Analytics & Financial Modelling

Developed by Harshita Chopra

This project demonstrates practical implementation of Python for banking data analytics, financial modelling, data cleaning, statistical analysis and visualization using real-world datasets.

---

# Project Overview

The project focuses on:
- Banking data analysis
- Financial modelling
- Candlestick chart visualization
- Bibliometric analysis
- Data preprocessing
- Statistical analytics
- Python automation

The project was created as part of the MGN342 CA2 assignment.

---

# Technologies Used

## Programming Language
- Python

## Libraries
- Pandas
- NumPy
- Matplotlib

## Tools
- PyCharm
- Excel
- Jupyter / Python IDE

---

# Project Features

- CSV Data Processing
- Missing Value Handling
- Duplicate Removal
- Data Cleaning
- Statistical Analysis
- Financial Ratio Analysis
- Group-wise Analytics
- Data Visualization
- Banking Dataset Analysis

---

# Topics Covered

## 1. Attention Check Filtering

Rows failing the attention check were removed using filtering conditions.

Example:
```python
df = df[df['TAD'] == 1].copy()
```

---

## 2. Variable Selection

Required financial variables were selected from the dataset.

Example:
```python
VARS = ['EquityCapital','TotalLiabilities','TotalAssets']
```

---

## 3. Missing Value Handling

Rows with more than 50% missing values were removed.

---

## 4. Mean Imputation

Missing numeric values were replaced using column means.

---

## 5. Data Type Standardization

Numeric columns were converted into proper numeric formats.

---

## 6. Duplicate Removal

Duplicate rows were removed and column names standardized.

---

## 7. Dataset Summary

Performed:
- Shape Analysis
- Dataset Information
- Statistical Description

---

## 8. Statistical Calculations

Computed:
- Mean
- Median
- Minimum
- Maximum
- Standard Deviation

---

## 9. Derived Financial Metrics

Created new calculated columns such as:
- Debt to Equity Ratio
- Asset Utilization Ratio
- Investment Ratio

Example:
```python
df['debt_to_equity'] = df['Borrowings +'] / df['EquityCapital']
```

---

## 10. Conditional Filtering

Filtered rows based on:
- Total Assets
- Attention Check Variables

---

## 11. Group-wise Statistics

Performed group-based statistical analysis using:
```python
groupby()
```

---

# Additional Work Included

## Bibliometric Analysis

A bibliometric network analysis of Central Bank of India research was performed to identify thematic interconnections within banking studies. :contentReference[oaicite:0]{index=0}

---

## Candlestick Chart Visualization

Stock price movements of Central Bank of India were analyzed using candlestick charts to understand:
- Market trends
- Investor sentiment
- Open-High-Low-Close analysis :contentReference[oaicite:1]{index=1}

---

# Files Included

## Python Files
- Data cleaning scripts
- Financial modelling scripts
- Statistical analysis scripts

## CSV Files
- Banking datasets

## Screenshots
- PyCharm execution
- Data outputs
- Charts
- Analytics results

## PDF
- CA2 Presentation Report

---

# Learning Outcomes

Through this project, practical understanding was developed in:
- Python programming
- Data preprocessing
- Banking analytics
- Financial analysis
- Statistical computation
- Data visualization
- Real-world dataset handling

---

# Future Improvements

Future enhancements may include:
- SQL integration
- PostgreSQL database connection
- Power BI dashboards
- AI-based forecasting
- Interactive analytics systems

---

# Author

Harshita Chopra

Aspiring AI Automation & Digital Marketing Specialist

LinkedIn:
www.linkedin.com/in/harhitachopra19
