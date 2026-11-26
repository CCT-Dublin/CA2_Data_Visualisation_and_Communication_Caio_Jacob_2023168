# Online Retail Sales Analysis & Interactive Dashboard (CA2)

**Module:** Data Visualisation and Communication (Stage 4, Semester 1)  
**Programme:** BSc Computing and IT — CCT College Dublin  
**Student:** Caio Jacob (`2023168`)  
**Lecturer:** Taufique Ahmed  

---

## Project Overview

This repository contains the Continuous Assessment 2 (CA2) project analysing transactional sales data from a UK-based online gift wholesaler (`Online Retail.xlsx`). The project follows an end-to-end data analytics workflow:

1. **Project Introduction** — Business context, objectives, and key management questions.
2. **Data Understanding** — Dataset structure, data types, and initial descriptive overview.
3. **Data Quality & Cleaning** — Systematic inspection and justified handling of missing values, exact duplicates, cancelled transactions, non-product codes, and outliers.
4. **Feature Engineering** — Creation of business-relevant variables (`Revenue`, `YearMonth`, `DayOfWeek`, `Hour`, `Market`, `InvoiceValue`).
5. **Exploratory Data Analysis (EDA)** — Static visualisations (`Matplotlib` & `Seaborn`) covering temporal trends, operational patterns, product performance, regional distribution, and customer behaviour.
6. **Interactive Management Dashboard** — Interactive dashboard built with `Plotly` and `ipywidgets`, featuring dynamic KPI cards, multi-criteria filters, and complementary charts.
7. **Business Insights & Recommendations** — Actionable findings tailored for non-technical stakeholders.
8. **Limitations & Conclusion** — Critical evaluation of dataset constraints and analytical scope.
9. **References** — Sources formatted using Harvard Referencing.

---

## Repository Structure

```text
.
├── CA2_Online_Retail_Analysis.ipynb                 # Main Jupyter Notebook (analysis, EDA, dashboard)
├── CA2_AI_Declaration_Caio_Jacob_2023168.docx       # CCT Assessment Cover Page & AI Fluency Declaration
├── .gitignore                                       # Excludes raw data and temporary/checkpoint files
└── README.md                                        # Project documentation and setup guide
```

> **Note on Data:** Raw dataset files (`*.xlsx`) are intentionally excluded from version control in accordance with assessment guidelines. To execute the notebook locally, place `Online Retail.xlsx` in the repository root folder (or its parent directory).

---

## Tech Stack & Requirements

- Python 3.12+
- Jupyter Notebook
- `pandas` & `numpy` (data manipulation)
- `openpyxl` (reading `.xlsx` files)
- `matplotlib` & `seaborn` (static EDA visualisations)
- `plotly` & `ipywidgets` (interactive dashboard)

### Quick Setup

```bash
pip install pandas numpy openpyxl matplotlib seaborn plotly ipywidgets
jupyter notebook CA2_Online_Retail_Analysis.ipynb
```
