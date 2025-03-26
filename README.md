# California Housing Price Prediction

## Project Overview

This project develops a machine learning model to predict median house prices in California districts based on various features like location, population, income levels, and housing characteristics. The analysis uses the California Housing dataset derived from the 1990 U.S. census.

## Objective

To build an accurate predictive model for California housing prices that can assist real estate investors, policy makers, and individual homebuyers in making informed decisions.

## Repository Structure

```
california_housing_prediction/
│
├── data/                          # Data storage directory
│
├── notebooks/                     # Jupyter notebooks
│   └── housing-script.ipynb  # Main analysis notebook
│
├── models/                        # Saved model files
│   ├── california_housing_xgboost_model.joblib  # Serialized final model
│   └── model_features.joblib      # Required features list
│
└── reports/                       # Project reports and visualizations
    └── README.md                  # Detailed project overview and findings
```

## Key Findings

- Median income and geographic location are the most important factors influencing housing prices
- Our tuned XGBoost model achieved an RMSE of approximately $50-60K and an R² of around 0.85
- Engineered features like rooms per household and distance to major cities significantly improved model performance

## Tools Used

- Python
- Scikit-learn
- XGBoost
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook 
