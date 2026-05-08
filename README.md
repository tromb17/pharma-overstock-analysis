# Pharma Overstock Analysis

Portfolio project for analyzing excess inventory (overstock) in a pharmaceutical supply chain using Python, Pandas, and Excel.

## Overview

This project identifies products with stock levels exceeding current contractual demand.  
The analysis combines warehouse balances, contract data, and sales transactions to estimate overstock in units and monetary value.

All data is anonymized for portfolio purposes.

## Project tasks

- calculate overstock by product;
- estimate overstock value;
- identify non-contracted stock;
- aggregate results by manufacturer, manager, and region;
- export results to Excel summary tables.

## Data used

The analysis is based on three types of data:

- stock balances;
- contract / auction data;
- sales transactions.

## Main metrics

- **Избыток тек год** — excess stock in units;
- **Избыток тек год, р** — excess stock value;
- **Продано уп за нед** — weekly sales volume.

## Repository structure

```text
pharma-overstock-analysis/
├── data/
├── notebooks/
├── reports/
├── README.md
└── .gitignore
```

## Tech stack

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Excel

## Output

The final result is an Excel report with detailed data and summary tables for business review.

## Note

All product names, manufacturers, customers, and related business fields are anonymized.
