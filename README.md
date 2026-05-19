# Alzheimer's Disease — Multi-Dataset Exploratory Analysis

**MSc Data Science · University of Southern Queensland**

---

## Overview

Exploratory data analysis across three publicly available Alzheimer's disease datasets. The notebook covers data quality assessment, clinical variable distributions, brain volume trends and differential gene expression visualisation.

## Datasets

| File | Source | Description |
|------|--------|-------------|
| `A1.csv` | ADNI | Baseline clinical screening data (13,509 records) |
| `AA2.tsv` | Public | Differential gene expression — 19,488 genes with logFC and p-values |
| `A3.xlsx` | OASIS | Longitudinal MRI data — Demented vs Nondemented subjects (373 records) |
| `A4.csv` | ADNI | Patient demographics — age, education, cognitive onset year |

> Datasets are not included in this repository. ADNI data requires registration at [adni.loni.usc.edu](https://adni.loni.usc.edu). OASIS data is available at [oasis-brains.org](https://www.oasis-brains.org).

## Notebook Contents

| Section | Description |
|---------|-------------|
| 1. Setup & Data Loading | Import libraries, load all four datasets |
| 2. Missing Value Analysis | Column-level missing data summary across all datasets |
| 3. OASIS Clinical EDA | MMSE by group, age distribution, brain volume vs cognition |
| 4. OASIS Pairplot | Relationships between all numeric clinical variables |
| 5. Volcano Plot | Gene expression — upregulated vs downregulated genes |
| 6. ADNI Demographics | Age distribution and cognitive onset year |
| 7. Summary | Key findings and suggested next steps |

## Tools & Libraries

- Python 3.10
- `pandas`, `numpy` — data manipulation
- `matplotlib`, `seaborn` — visualisation
- `openpyxl` — Excel file support

## How to Run

```bash
pip install pandas numpy matplotlib seaborn openpyxl
jupyter notebook RS.ipynb
```

Place all data files (`A1.csv`, `AA2.tsv`, `A3.xlsx`, `A4.csv`) in the same directory as the notebook before running.

---

*Part of MSc Data Science coursework at the University of Southern Queensland.*
