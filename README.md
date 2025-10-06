# Predicting-the-Beats-per-Minute-of-Songs

In this notebook, I build a regression model to predict the Beats Per Minute (BPM) of songs based on their metadata and features. The workflow covers:

✅ Data preprocessing (handling missing values, feature scaling, train-test split)
✅ Model training using LightGBM Regressor
✅ RMSE evaluation with early stopping and callbacks
✅ Hyperparameter tuning for better performance
✅ Generating submission files for the competition

Highlights:

-Uses LightGBM for fast and accurate gradient boosting.
-Achieved improved RMSE score through feature scaling, validation strategy, and parameter tuning.
-Well-structured pipeline that can be extended with feature engineering and ensembling.
