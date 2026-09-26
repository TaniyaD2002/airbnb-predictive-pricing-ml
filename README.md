# Airbnb Predictive Pricing Machine Learning Pipeline

## Overview
An end-to-end machine learning pipeline developed in Python to predict nightly prices for Airbnb listings in Melbourne. This project encompasses exploratory data analysis (EDA), extensive feature engineering, and the training and evaluation of multiple machine learning algorithms. 

*Note: Due to licensing restrictions on the dataset, the raw data files are not included in this repository. The code demonstrates the methodology and pipeline architecture.*

## Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
* **Environment:** Jupyter Notebook

## Key Achievements
* Achieved top-10% cohort accuracy (95/100 score).
* Engineered features handling geographical data (WGS84 projection coordinates), categorical data, and host metrics.
* Conducted hyper-parameter tuning on the Alpha ($\alpha$) regularization parameter for the Lasso and Ridge models to optimize model performance.

## Methodology
1. **Data Pre-Processing:** Cleaned and formatted data, handled missing values, and encoded categorical variables (e.g., room_type, city).
2. **Feature Engineering:** Extracted relevant signals from property characteristics and review scores to improve predictive power.
3. **Model Selection:** Evaluated multiple linear regression variants to determine the optimal algorithm for price prediction.
4. **Evaluation:** Validated the model using rigorous performance measures to ensure real-world applicability.
