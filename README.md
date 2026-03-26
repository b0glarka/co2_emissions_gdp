# Assignment 2: CO2 Emissions and GDP - Panel Data Analysis

ECBS5245 - Data Analysis 4: Causal Analysis (advanced)
Boga Petruska, March 2026

## Overview

Panel data analysis examining the relationship between GDP per capita and CO2 emissions per capita across 189 countries from 1992 to 2024. Estimates cross-sectional OLS, first-difference, and two-way fixed effects models with clustered standard errors. Urbanization is explored as a confounder.

## Files

| File | Description |
|---|---|
| `Petruska_Assignment_2.pdf` | Final report (PDF) |
| `Petruska_Assignment_2.md` | Report source (Markdown) |
| `Petruska_Assignment_2.ipynb` | Analysis notebook (Python) |
| `header.tex` | LaTeX header for pandoc PDF compilation |
| `output/` | Exported figures (.png) and tables (.tex) |
| `data/` | Raw World Bank data (CSV) |
| `requirements.txt` | Python dependencies |


## Reproducing

1. Install dependencies: `pip install -r requirements.txt`
2. Run the notebook: open `Petruska_Assignment_2.ipynb`, Restart Kernel and Run All
3. Build the PDF: `pandoc Petruska_Assignment_2.md -o Petruska_Assignment_2.pdf --pdf-engine=xelatex -V geometry:margin=1in -H header.tex`

Requires pandoc and a LaTeX distribution (e.g., MiKTeX) for PDF generation.

## Data Sources

- World Bank World Development Indicators (GDP, population, CO2 emissions)
- World Bank API (urbanization, income group classification)
