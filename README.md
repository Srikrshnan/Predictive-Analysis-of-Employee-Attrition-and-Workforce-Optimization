# Predictive Analysis of Employee Attrition and Workforce Optimization

This project analyzes employee attrition patterns and aims to provide insights that support workforce optimization. The analysis is based on a dataset of 100,000 entries across 26 features.

## 📊 Objective

The goal of this notebook is to identify key factors that contribute to employee attrition and provide data-driven strategies for employee retention.

## 🗃️ Dataset Overview

- **Rows**: 100,000
- **Columns**: 26
- The dataset contains both numerical and categorical features.
- Missing values were identified in `ReasonForAttrition` and `BusinessTravel`.

## 🔍 Key Steps in the Analysis

1. **Data Cleaning**
   - Removed duplicates (none found).
   - Dropped logically redundant columns like `Years in Current Role` vs `Years Since Last Promotion`.
   - Dropped identifier columns like `Emp ID`.
   - Reclassified certain numerical columns as categorical.

2. **Missing Value Treatment**
   - `BusinessTravel`: Imputed using mode.

3. **Data Type Segregation**
   - Categorical and numerical features separated for appropriate analysis.

4. **Statistical Analysis**
   - Descriptive statistics computed for both categorical and numerical columns.
   - Initial visualizations of attrition patterns.

## 🧰 Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

## 🚀 Getting Started

To run this notebook:

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/basic-modeling.git
   cd basic-modeling
