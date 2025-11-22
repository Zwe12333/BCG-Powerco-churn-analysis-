# BCG PowerCo Churn Analysis

Exploratory Data Analysis (EDA) for BCG PowerCo's customer churn prediction case study using Python and Jupyter Notebook.

## Overview
This repository contains a Jupyter Notebook for analyzing customer churn data from BCG's PowerCo case. The analysis includes:
- Data loading and cleaning
- Descriptive statistics and data types
- Visualizations of distributions, correlations, and price sensitivity
- Key insights on churn rates, customer behavior, and pricing trends

The notebook uses libraries like Pandas, Matplotlib, and Seaborn to explore two datasets: client data (consumption, forecasts, churn) and historical pricing data.

## Datasets
- `client_data (1).csv`: Customer details, consumption, and churn indicators.
- `price_data (1).csv`: Historical variable and fixed prices.

(Note: Datasets are not included in this repo due to size/privacy; reference them in your local environment.)

## How to Run
1. Clone the repo: `git clone https://github.com/your-username/bcg-powerco-churn-analysis.git`
2. Install dependencies: `pip install pandas numpy matplotlib seaborn`
3. Open in Jupyter: `jupyter notebook bcg_x_churn.ipynb`
4. Or use Google Colab: Upload the .ipynb to colab.research.google.com and run.

## Key Insights
- Churn rate: ~9.72% (imbalanced dataset).
- Most customers (~81.8%) use electricity only.
- Consumption and margins are right-skewed—log transforms recommended for modeling.
- Prices varied in 2015, highlighting potential sensitivity features.

## Next Steps
This EDA sets up for modeling (e.g., Logistic Regression or XGBoost). Future work: Feature engineering and predictive modeling.

## License
MIT License—feel free to use and adapt.

Author: Hlangalezwe Zulu| Date: November 23, 2025
