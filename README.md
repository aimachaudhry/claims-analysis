# Healthcare Claims Data Analysis

## Project Overview

A sample of prospective claims data from May 2024 at Stony Brook University Hospital has been provided. In this assignment, I have analyzed billing patterns, identified the most common diagnoses and procedures, and supported operational-decision making. Overall, claims data can be used in understanding revenue cycle management, coding accuracy audits, payer contract analysis, clincial quality reporting, and healthcare operations optimization. 

## Data Sources

- **HEADER File**: Contains one row per claim with high-level information

- **LINE File**: Contains one row per service line (procedures/services)

- **CODE File**: Contains diagnosis codes (ICD-10)

## How to Run Notebook:

1. Open notebook in Colab

2. Upload the CSVs
   ```
   from google.colab import files
   files.upload()
   ```

2. Run all cells

## Required Libraries

```
   pandas>=1.3.0
   matplotlib>=3.4.0
   seaborn>=0.11.0
   ```

## Key Findings
### Part 1: Data Loading and Exploration 

