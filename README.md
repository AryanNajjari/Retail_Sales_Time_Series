# Project Overview

This project focuses on building and evaluating time series models for sales revenue prediction using a dataset with limited original features. The goal is to assess how effectively different models can learn historical sales patterns and generalize to unseen data.

# Dataset Description

## The original dataset contains a minimal set of features, including:

Store identifiers

Promotion status (promotion vs. no promotion)

Holiday indicator (holiday vs. non-holiday)

Sales revenue

Date of transaction

Since time series performance heavily depends on temporal patterns, additional date-based features were extracted from the date column to enrich the dataset. These engineered features include components such as day, week, month, and other calendar-related indicators, enabling the models to better capture seasonality, trends, and temporal dependencies.

# Feature Engineering

To improve predictive performance and dataset reliability:

Temporal features were derived directly from the date column.

Categorical indicators (promotion and holiday flags) were retained to capture external influences on sales behavior.

The resulting dataset was structured to ensure consistency and suitability for time series modeling.

# Modeling and Evaluation

The models were trained on historical data and evaluated on a held-out test set to assess their generalization capability. Model performance is demonstrated through visual comparisons between:

Actual sales values

Model predictions on training data

Model predictions on test data

These visualizations provide intuitive insight into how well each model learns temporal patterns and how accurately it forecasts future sales revenue.

# Results and Insights

The project emphasizes:

The impact of temporal feature extraction on model performance

The ability of time series models to capture seasonality and trends

Visual interpretability of predictions for both training and test datasets

This work serves as a foundation for scalable sales forecasting pipelines and can be extended with additional external features or more advanced time series architectures.
