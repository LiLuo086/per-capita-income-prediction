# Per-Capita Income Prediction — Linear vs. Polynomial Regression

## Project Overview

This project forecasts per-capita income from year using a compact, transparent ML workflow. Starting with a simple linear regression baseline, I compare it against polynomial regression to capture possible non-linear trends.

The notebook uses `scikit-learn` for modeling, `train_test_split` for a clean hold-out evaluation, and cross-validation to compare model variants. Performance is summarized with MSE/RMSE, and results are visualized with matplotlib (scatter + fitted curve) for an intuitive read on model fit.

### Dataset

The pubic dataset [Canada_per_capita_income](https://www.kaggle.com/datasets/amalab182/canada-per-capita-income) provides the average income per capita over a specific period(from 1970 to 2016) in Canada and includes totally 47 rows and 2 columns: **year** and **income**. The information contained in this dataset can help people better understand the economic trends in Canada.

### Technologies

Python, scikit-learn (linearRegression, polynomial features), train_test_split, cross-validation, RMSE/MSE, matplotlib.
