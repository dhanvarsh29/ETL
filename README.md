# Task 14 — ETL Mini Pipeline (Python)

## Objective
Build a mini ETL pipeline using Python to extract raw data, transform it, and load outputs into CSV and SQLite.

---

## Tools Used
- Python (Google Colab)
- pandas
- SQLite

---

## ETL Steps

### Extract
- Loaded raw retail sales dataset from `raw/`

### Transform
- Removed duplicates
- Filled missing values
- Standardized column names
- Created derived columns:
  - Profit Margin %
  - High Value Order Flag

### Load
- Exported cleaned dataset into `processed/`
- Split into separate tables:
  - Customers
  - Orders
  - Products
- Loaded tables into SQLite database (`database.sqlite`)

---

## Output Files
- processed/processed_data.csv
- output/customers.csv
- output/orders.csv
- output/products.csv
- database.sqlite

---

## Outcome
This task demonstrates how real-world ETL pipelines work in analytics workflows.
