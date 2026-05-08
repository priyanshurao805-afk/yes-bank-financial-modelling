# yes-bank-financial-modelling
Financial modelling and analysis of Yes Bank using Python, Pandas, SQL, and PostgreSQL.
# Yes Bank Financial Modelling & Analysis

## Overview
This project focuses on the financial modelling and analysis of Yes Bank using Python, Pandas, SQL, and PostgreSQL. The project includes data preprocessing, financial ratio analysis, statistical analysis, and database connectivity for banking data analytics.

---

## Objectives
- Analyze financial performance of Yes Bank
- Perform data cleaning and preprocessing
- Calculate important financial ratios
- Connect PostgreSQL with Python
- Generate insights from banking data

---

## Technologies Used
- Python
- Pandas
- NumPy
- PostgreSQL
- SQL
- Psycopg2
- PyCharm

---

## Tasks Performed
- Data Cleaning
- Missing Value Handling
- Duplicate Removal
- Statistical Analysis
- Financial Ratio Analysis
- GroupBy Operations
- Database Connectivity
- Data Transformation

---

## Financial Ratios Calculated
### Debt to Equity Ratio
Measures company leverage and financial risk.

### Asset Utilization Ratio
Shows how efficiently assets are used.

### Investment Ratio
Analyzes investment contribution to total assets.

---

## Sample Code

```python
import psycopg2
import pandas as pd

conn = psycopg2.connect(
    host="localhost",
    port="5432",
    dbname="postgres",
    user="postgres",
    password="your_password"
)

df = pd.read_sql(
    "SELECT * FROM public.final_yesbank;",
    conn
)

print(df.head())

conn.close()
```

---

## Key Learning Outcomes
- Financial data analysis using Python
- SQL database connectivity
- Banking sector analytics
- Data preprocessing using Pandas
- Financial modelling concepts
- Statistical data analysis

---

## Project Features
- PostgreSQL Database Integration
- Banking Dataset Analysis
- Financial KPI Evaluation
- Data Visualization Support
- Real-world Financial Analytics

---

## Conclusion
This project helped in understanding real-world financial modelling and banking analytics using Python and PostgreSQL. It improved practical knowledge of SQL, data preprocessing, and financial ratio analysis.

---

## Author
### Priyanshu Kumar Rao
