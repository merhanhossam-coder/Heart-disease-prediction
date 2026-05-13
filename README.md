# Heart Disease Dataset – Exploratory Data Analysis (EDA)

This repository contains an Exploratory Data Analysis (EDA) workflow for a Heart Disease dataset using Python.  
It covers basic inspection, cleaning (duplicate removal), summary statistics, categorical value counts, and boxplots for numeric features.

---

## Dataset Overview

- Rows: **1025** (before cleaning)
- Columns: **14**
- Missing values: **None**
- Duplicates: **Detected and removed**
- Target column: `target` (0/1)

Columns:
`age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target`

---

## What This EDA Does

- Loads the dataset with **pandas**
- Displays sample rows (`head`)
- Checks dataset info (`info`) and data types (`dtypes`)
- Generates descriptive statistics (`describe`)
- Checks missing values (`isnull().sum()`)
- Detects and removes duplicates (`duplicated()`, `drop_duplicates()`)
- Shows value counts for categorical features:
  - `cp`, `restecg`, `thal`
- Draws boxplots for all numeric columns using **seaborn** + **matplotlib**

---

## Setup

Install required packages:

```bash
pip install -r requirements.txt
```

## Create a requirements.txt file with:
```bash
pandas
numpy
matplotlib
seaborn
```
