# Machine-Learned Factor Momentum: Timing Equity Factors with Gradient Boosted Trees

This master's thesis uses XGBoost, LightGBM, and CatBoost in Python to forecast returns across 48 equity factors and construct factor momentum strategies over 1985–2024.

The analysis uses time-series cross-validation, Bayesian hyperparameter optimisation, and expanding and fixed-window training schemes for out-of-sample forecasting. It compares traditional and machine-learned time-series and cross-sectional factor momentum.

In the thesis analysis, machine-learned factor momentum generally improved Sharpe ratios. Machine-learned time-series factor momentum strategies also generated positive and statistically significant alpha relative to traditional factor momentum.

- [Thesis PDF](Thesis.pdf): submitted thesis.
- [Main notebook](main_file.ipynb): factor construction, forecasting, portfolio strategies, and performance analysis.
- [Exploratory notebook](exploratory_neural_networks.ipynb): neural-network experiments excluded from the submitted thesis.
