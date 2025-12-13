# youtube-analysis
In this project, I analyzed whether comments will be disabled or enabled on videos, implemented a few models (CART, Multiple Linear Regression), and cross validated my results. Real-life examples are included. 
---
# YouTube Data Analysis Notebook

## Overview
This Jupyter Notebook explores and models YouTube engagement metrics, such as views, likes, dislikes, and comments. It demonstrates:

- Data cleaning and preprocessing
- Predictive modeling using:
  - Decision Tree Classifier (for predicting whether comments are disabled)
  - Decision Tree Regressor (for predicting views)
  - Multiple Linear Regression
  - Ridge and Lasso regression
- Model evaluation with R², MAE, and classification metrics
- Cross-validation and hyperparameter tuning
- Visualization of regression/classification trees and prediction results

This work was developed as part of a research-oriented data analysis project and is included here as part of my PhD application materials.

---

## Files
- `YouTube_Analysis.ipynb` – The main Jupyter Notebook containing all code, outputs, and visualizations.

---

## Requirements
To run this notebook, you need:

- Python 3.8+
- Libraries:
  ```text
  pandas
  numpy
  matplotlib
  seaborn
  scikit-learn
  plotly
  dmba
