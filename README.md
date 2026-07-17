# Vendor Performance and Inventory Analysis

This repository contains a small inventory analytics workflow built around vendor sales, product turnover, and performance summaries.

## Contents

- `Exploratory Data Analysis.ipynb` for initial inspection and trends
- `ingestion_db.ipynb` for loading raw data into a database workflow
- `get_vendor_summary.ipynb` for vendor-level summary extraction
- `Vendor Performance Analysis.ipynb` for analysis and reporting
- CSV and Excel outputs under the project root and `Tables from Database/`

## Data

The repository includes processed and summary outputs used for analysis. Two very large raw files are kept out of Git because GitHub rejects files over 100 MB:

- `data/purchases.csv`
- `data/sales.csv`

If you need those files locally, place them in the `data/` folder before running the ingestion notebook.

## Notes

- `logs/` and notebook checkpoint files are ignored by Git.
- The repo is intended for analysis and reporting, not as a production application.