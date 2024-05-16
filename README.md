# cholesterol-prediction-mcf-itb
My journey on accomplished Data Science Competition held by ITB (Institut Teknologi Bandung). Dealing imbalanced dataset of cholesterol total as the target, both from Classification Regression.

In summary, here's an overview of the steps I've taken:
- General Preparation: Analyzed pair plots for outlier detection, handled categorical encoding for gender, and selected features based on medical reasoning using pandas, numpy, and seaborn.
- Classification Preparation: Defined cholesterol thresholds for classification, performed additional outlier handling, and used ordinal encoding for age range and BMI categories with sklearn's preprocessing tools.
- Regression Preparation: Enhanced data quality by dropping duplicate rows on the target variable using pandas.
- Classification Model: Implemented an XGBoost Classifier, optimized n_estimators to handle imbalanced data, achieving a recall score of 0.97 on validation data and 0.93 on test data. Utilized sklearn's model_selection and metrics tools for model evaluation.
- Regression Model: Employed an XGBoost Regressor, achieving a Root Mean Square Error (RMSE) of 31.96 in cross-validation using sklearn's mean_squared_error metric.
- Additional Techniques: Utilized KNNImputer for handling missing data, and SHAP for model interpretability. Managed warnings using Python's warnings library.

> P.S: The notebook is a bit messy, i'm going to update it asap!
