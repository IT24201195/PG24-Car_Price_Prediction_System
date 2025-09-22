
# Car Price Prediction Project – Progress Evaluation

This repository contains the structure and Jupyter notebooks required for the car price prediction project.  Each team member is responsible for a specific preprocessing technique and has been assigned a separate notebook.  The goal is to collaboratively build a complete preprocessing pipeline and train a model to predict used car prices.

## Directory Structure

```
car_price_prediction_project/
├── data/
│   ├── train-data.csv      # training dataset (place your CSV here)
│   └── test-data.csv       # test dataset (place your CSV here)
├── notebooks/
│   ├── 1_IT24104304_initial_cleaning.ipynb    # drop irrelevant columns & duplicates
│   ├── 2_IT24104241_missing_value_imputation.ipynb  # handle missing values
│   ├── 3_IT24104194_numeric_conversion.ipynb  # convert textual numbers to numeric
│   ├── 4_IT24201195_categorical_encoding.ipynb  # encode categorical variables
│   ├── 5_IT24104332_feature_scaling.ipynb     # scale numerical features
│   ├── 6_IT24104348_outlier_detection.ipynb   # detect and remove outliers
│   ├── 7_preprocessing_pipeline.ipynb         # integrate all preprocessing steps
│   └── 8_model_training.ipynb                 # train and evaluate the model
└── README.md
```


1. **Initial cleaning** removes obviously irrelevant information and duplicates (IT24104304).
2. **Missing value imputation** (IT24104241) ensures that algorithms receive complete numeric and categorical data.
3. **Numeric conversion** (IT24104194) extracts numbers from strings like `"26.6 kmpl"` and `"998 CC"`.
4. **Categorical encoding** (IT24201195) transforms string labels into numerical vectors and groups rare names into an `Other` category.
5. **Feature scaling** (IT24104332) standardises numeric columns.
6. **Outlier detection and treatment** (IT24104348) removes extreme values from the training set to improve model robustness.

