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
- The dataset contains 388 unique claims from Sept 2023 to May 2024
- **Top providers**: SB INTERNISTS, SB SURGICAL ASSOCIATES, and NEW YORK SPINE AND BRAIN SURGERY billed the most claims
- **Most common payers**: MEDICARE has ~62% of claims, then HEALTHFIRST FFS and FIDELIS/BETTER HEALTH PLAN
- **Most Frequent diagnoses**: J96.01 (Acute respiratory failure)
- **Top procedure**: 99291 (Critical Care, Initial Hour)
- **Most claims are inpatient** 
- **Average charges by location**: On-campus outpatient hospital claims are highest, followed by inpatient, office visits, and emergency room

