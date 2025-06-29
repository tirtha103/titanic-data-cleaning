# Titanic Data Cleaning & Pre-processing 
![Python](https://img.shields.io/badge/Made%20with-Python-blue?logo=python)

**Author:** Tirtha Dutta  
**Date:** 23 June 2025  
**Dataset:** [Kaggle – Yasser H Titanic Dataset](https://www.kaggle.com/datasets/yasserh/titanic-dataset)

---

##  Objective

This project walks through a simple, step-by-step data cleaning and preprocessing pipeline that is friendly even for beginners. The key steps include:

1. **Load & inspect** nulls + data types  
2. **Handle missing values** (median / mode, drop `Cabin`)  
3. **Encode categoricals** (`Sex`, `Embarked`)  
4. **Standardize numerics** (`Age`, `Fare`)  
5. **Detect & trim outliers** using boxplots + IQR  
6. **Save** a clean dataset as `titanic_cleaned.csv`

---

##  Quick Start

To run this project locally:

```bash
git clone https://github.com/tirtha103/titanic-data-cleaning.git
cd titanic-data-cleaning

# Create and activate virtual environment (Windows)
python -m venv venv
venv\Scripts\activate

# Install required packages
pip install -r requirements.txt

# Launch the notebook
jupyter lab notebooks/01_cleaning_walkthrough.ipynb