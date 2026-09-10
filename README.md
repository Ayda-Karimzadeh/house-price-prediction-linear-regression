# California Housing Price Prediction

A machine learning project to predict median house values across California districts using demographic and housing data from the 1990 U.S. Census.

## Overview

This project builds a complete, end-to-end regression pipeline — from data understanding through model evaluation — to predict `median_house_value` based on features like location, housing supply, population density, and median income.

Because the underlying data is from 1990, the resulting model is not intended for real-time, market-accurate price estimates. Instead, the project serves as a methodological foundation: the same pipeline (data preparation, feature engineering, model selection, evaluation) is designed to be reapplied later to current, live housing data as part of a broader real-estate pricing platform.

## Dataset

[California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices) (Kaggle) — median house prices for California districts, derived from the 1990 census. 20,640 records, 10 features.

## Project Structure

```
├── data/
│   └── housing.csv
├── notebooks/
│   ├── 00_business_understanding.ipynb
│   ├── 01_data_understanding.ipynb
│   └── ...
├── requirements.txt
└── README.md
```

## Workflow

0. **Business Understanding** — problem definition, objectives, success criteria
1. **Data Understanding** — structure, data types, missing values, duplicates, initial statistics
2. **Data Preparation** — cleaning, handling missing values, feature engineering
3. **Exploratory Data Analysis** — relationships between features and target
4. **Modeling** — regression model training and comparison
5. **Evaluation** — MAE, MSE, RMSE on held-out data

## Status

🚧 In progress — currently at the Data Understanding stage.

## Requirements

```
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter

```

## Author

Ayda Karimzadeh — [GitHub](https://github.com/Ayda-Karimzadeh) · [LinkedIn](https://www.linkedin.com/in/ayda-karimzadeh/)