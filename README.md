# Istanbul Water Consumption Forecasting

## Comparative Analysis of Classical Time Series, Machine Learning, and Foundation Models

This repository contains my undergraduate Industrial Engineering graduation project, which investigates district-level water consumption forecasting in Istanbul. The study compares the predictive performance of ten forecasting models, including classical time series methods, machine learning algorithms, and recent foundation models for time series forecasting.

## Project Objective

The objective of this study is to forecast monthly district-level water consumption in Istanbul and compare different forecasting approaches to identify the most accurate and reliable model.

## Dataset

The models were trained using monthly data (2020–2025), including:

* Monthly water consumption
* Residential subscriber counts
* Commercial subscriber counts
* Average temperature


> **Note:** The original dataset is not included in this repository due to data-sharing restrictions.

## Forecasting Models

### Classical Time Series Models

* Prophet
* SARIMAX

### Machine Learning Models

* Decision Tree
* Random Forest
* XGBoost
* LightGBM (LGBM)
* LSTM

### Foundation Models

* TimeGPT
* TimesFM
* Chronos

## Model Evaluation

The forecasting models were evaluated using:

* MAE
* MSE
* RMSE
* MAPE
* R²

## Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* LightGBM
* XGBoost
* TensorFlow / Keras
* Prophet
* Statsmodels
* TimeGPT
* TimesFM
* Chronos
* Matplotlib
* Jupyter Notebook

## Repository Structure

```text
data/
notebooks/
models/
results/
figures/
README.md
requirements.txt
```

## Author

**Damla Gökdeli**

Industrial Engineering Undergraduate
Graduation Project – Istanbul University-Cerrahpaşa
