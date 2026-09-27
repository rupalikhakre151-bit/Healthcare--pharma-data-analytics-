# Healthcare / Pharmaceutical Data Cleaning & Analysis

## Project Overview
This project demonstrates practical data-cleaning and exploratory-analysis skills using a pharmaceutical product dataset.

### Dataset
- Original records: **114,223**
- Columns: **18**
- Exact duplicate rows: **83,618**
- Records after duplicate removal: **30,605**
- Unique product IDs: **30,604**
- Unique proprietary names: **11,008**
- Unique labelers: **1,413**

## Objectives
1. Understand the structure and data types of a healthcare/pharmaceutical dataset.
2. Identify missing values and duplicate records.
3. Clean duplicate records and standardize text/date fields.
4. Analyze product names, dosage forms, routes, marketing categories, and labelers.
5. Produce visualizations that communicate key findings.

## Key Cleaning Steps
- Read the CSV using `latin1` encoding.
- Standardized column names to uppercase.
- Removed leading/trailing whitespace from text fields.
- Identified and removed exact duplicate rows.
- Converted marketing-date fields into date format where possible.
- Calculated missing-value summaries.

## Analysis
The notebook includes:
- Dataset shape and information
- Numerical vs categorical column identification
- Missing-value analysis
- Duplicate-record analysis
- Unique product and labeler counts
- Top proprietary names
- Top dosage forms
- Top administration routes
- Top labelers
- Marketing-category distribution
- Basic charts

## Important Note
This dataset is **pharmaceutical product-level data**, not patient-level clinical data. Therefore, patient count, average patient age, disease prevalence, and gender distribution are not applicable to this dataset.

## Repository Structure
```text
Healthcare-Pharma-Data-Analysis/
├── data/
│   └── pharma_data_cleaned.csv
├── notebooks/
│   └── Healthcare_Pharma_Analysis.ipynb
├── outputs/
│   └── charts/
├── README.md
└── requirements.txt
```

## Tools
- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Author
**Rupali Khakre**
