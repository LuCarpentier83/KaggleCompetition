# Kaggle

My work on Kaggle competitions and datasets: exploratory analysis, data cleaning, feature
engineering, model selection and hyperparameter tuning.

## Projects

| Folder | Problem | Techniques |
|---|---|---|
| `Titanic` | Predict passenger survival (classification) | Scikit-learn pipelines and `ColumnTransformer`, custom transformers, GridSearchCV, RandomizedSearchCV, Bayesian search, Optuna |
| `HousePricePrediction` | Predict house sale prices (regression) | Data cleaning, linear models with statsmodels, neural network with TensorFlow |
| `LoanApproval` | Predict loan approval (Playground Series) | Data cleaning, XGBoost, hyperparameter tuning with Optuna |
| `HeartDisease` | Predict heart disease (Playground Series S6E2) | Data exploration, random forest (with notes on the math), XGBoost |
| `Hydrodynamics` | Predict the residuary resistance of sailing yachts (UCI yacht hydrodynamics) | Keras model built with the Subclassing API, TensorBoard |
| `Stocks` | Stock price forecasting | Alpha Vantage and Yahoo Finance data, moving averages, LSTM and GRU with TensorFlow, RNN with PyTorch, TensorFlow time-series tutorial |

## Getting started

```bash
pip install -r requirements.txt
jupyter lab
```

Competition data can be downloaded with the Kaggle CLI, for example
`kaggle competitions download -c titanic`.
