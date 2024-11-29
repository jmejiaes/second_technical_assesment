# second_technical_assesment

This repository contains the technical assessment for forecasting container service prices. The project is structured to analyze historical data, develop predictive models, and track performance metrics.

## Project Structure

```
second_technical_assesment
├── data
│   ├── input
│   │   └── sample.csv                   # Original input dataset
│   └── output
│       ├── average_metrics.csv          # Summary metrics for model performance
│       ├── bayesian_degradation_metric.png # Plot showing degradation metric over iterations
│       ├── bayesian_forecast.png        # Bayesian model predictions vs actual values
│       ├── bayesian_results.csv         # Results from Bayesian model iterations
│       ├── nn_forecast.png              # Neural network model predictions vs actual values
│       ├── price_time_series_decomposition.png # Seasonal decomposition of the time series
│       ├── price_time_series.png        # Plot of average container service price per day
│       ├── price_time_series_sundays.png # Plot of the price series with markers for Sundays
│       └── sample_corrected.csv         # Corrected input dataset
├── develop.ipynb                        # Jupyter notebook with code for data analysis and modeling
├── requirements.txt                     # Dependencies required to run the project
```

## Overview

This project aims to forecast container service prices using both Bayesian inference and Neural Network approaches. The analysis involves:
- Data cleaning and augmentation.
- Time series visualization and decomposition.
- Model training and performance evaluation.

## Key Components
- **Data Analysis**: Conducted in `develop.ipynb`, involving visualizations and decompositions of the time series.
- **Bayesian Model**: Implements a Bayesian inference approach to predict future container service prices (`bayesian_forecast.png`).
- **Neural Network Model**: Uses a Convolutional Neural Network for forecasting (`nn_forecast.png`).

## Outputs
- Visualizations of the time series (`price_time_series.png`) and its decomposition (`price_time_series_decomposition.png`).
- Forecast comparisons for both Bayesian and Neural Network models.
- Metrics (`average_metrics.csv`) detailing model performance, including MAPE and degradation metrics.

## Getting Started
To replicate the results or explore further, use the following steps:
1. Install the required packages: `pip install -r requirements.txt`
2. Run the notebook `develop.ipynb` for data analysis, modeling, and visualization.
