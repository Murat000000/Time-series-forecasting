# Time Series Forecasting: Corporación Favorita Grocery Sales

## 📌 Project Overview
This project addresses a large-scale time series forecasting problem for Corporación Favorita, a large Ecuadorian grocery retailer. The primary objective is to predict daily unit sales for various product families across 54 unique stores.

The project involves processing millions of rows of historical data to capture complex patterns driven by seasonality, holidays, and external economic factors like oil prices.

## 🎯 Objectives
The goal of this assignment is to build, train, and evaluate three distinct categories of forecasting models to handle high-dimensional data. The project compares the implementation and practical trade-offs of:

1.  **Classical Time Series:** Seasonal ARIMA with exogenous variables (SARIMAX) to capture weekly cycles.
2.  **Machine Learning:** Gradient boosting regression using **CatBoost** and **Random Forest** for efficient handling of categorical features.
3.  **Deep Learning:** 1D Convolutional Neural Networks (CNN) and Artificial Neural Networks (ANN).

All models are evaluated using the Root Mean Squared Logarithmic Error (RMSLE) metric.

## 📂 Repository Structure
This repository contains the code and documentation for the analysis:

* **`TSF_FA.ipynb`**: The main Jupyter Notebook containing data cleaning, feature engineering, visualization, and the implementation of all forecasting models (SARIMAX, CatBoost, ANN/CNN, and Random Forest).
* **`Time Series Forecasting Project.pdf`**: The comprehensive project report detailing the methodology, data analysis, and final conclusions.
* **`TSF_FA.pdf`**: A PDF export of the analysis notebook.
* **`TSF_FA.zip`**: Compressed archive containing the project resources/dataset samples.

## 📊 Data Source
The dataset is sourced from the **Store Sales - Time Series Forecasting** competition on Kaggle. It includes:
* **Train/Test Data:** Historical daily sales.
* **Metadata:** Store location, type, and cluster.
* **Events:** Holidays, promotions, and daily oil prices.

## 🚀 Getting Started
To replicate the analysis:
1.  Clone this repository.
2.  Ensure you have the required Python libraries installed (pandas, numpy, statsmodels, catboost, tensorflow/keras, sklearn).
3.  Unzip `TSF_FA.zip` to access the data files.
4.  Run `TSF_FA.ipynb` to execute the training and evaluation pipeline.
