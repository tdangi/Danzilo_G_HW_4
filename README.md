# Danzilo_G_HW_4

## Overview
This homework analyzes hospital cost and pricing data using the Hospital Cost Report 
Information System (HCRIS). The analysis covers hospital pricing trends, penalization 
under the Hospital Readmissions Reduction Program (HRRP) and Value-Based Purchasing 
(VBP) program, and instrumental variables (IV) estimation of the effect of penalties 
on hospital prices.

## Data
- Raw data used: HCRIS (1996, 2010 versions), covering years 2009–2019
- Data is NOT included in this repo — point file paths to your local HCRIS data files
- Additional data: HRRP/VBP penalty data for 2012–2019

## Files
- `Danzilo_G_HW_4_3.ipynb` – **Main notebook (use this one)**: full analysis including
  data cleaning, price estimation, visualizations, OLS and IV regressions
- `Danzilo_G_HW_4_1.ipynb` – Early attempt / troubleshooting (ignore)
- `Danzilo_G_HW_4_2.ipynb` – Early attempt / troubleshooting (ignore)
- `HCRIS_1996.ipynb` – Loads and processes the HCRIS 1996 data format
- `HCRIS_2010.ipynb` – Loads and processes the HCRIS 2010 data format
- `hcris_combine.ipynb` – Combines both HCRIS formats into one dataset
- `Danzilo_G_HW_4_3.pdf` – PDF export of the final notebook

## How to Run
1. Clone the repo
2. Run `HCRIS_1996.ipynb` and `HCRIS_2010.ipynb` to process raw data
3. Run `hcris_combine.ipynb` to merge into a single dataset
4. Run `Danzilo_G_HW_4_3.ipynb` for the full analysis
> Make sure to update file paths to point to your local copies of the raw HCRIS data

## Language
Python (Jupyter Notebooks)
