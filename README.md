# 🌫️ Air Pollution Prediction using Gradient Boosting Machine

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Model-LightGBM-orange.svg)](https://lightgbm.readthedocs.io/)

## Overview
This project builds a **Gradient Boosting Machine (GBM)** model to predict atmospheric pollutant concentrations (e.g., $CO$, $NO_2$, $NO_x$) based on historical air quality sensor readings.

## Features
- **Data Preprocessing:** Automated cleaning, outlier detection, and missing value imputation.
- **Feature Engineering:** Temporal features (hour, day, month) and rolling averages.
- **Model Training:** Hyperparameter tuning using LightGBM / Scikit-Learn.
- **Evaluation:** Visual and statistical comparison between actual vs. predicted values.

## Dataset
This project utilizes the **[Air Quality Data Set](https://www.kaggle.com/datasets/fedesoriano/air-quality-data-set)** sourced from Kaggle. 

The dataset contains **9,358 hourly records** collected across 15 variables in the city of Milan between 2004 and 2005 using automated sensors. It includes:
- **Atmospheric Pollutants:** Concentrations of $CO$, $NO_x$, $NO_2$, and other compounds.
- **Meteorological Conditions:** Temperature, relative humidity, and wind speed.
- **Temporal Markers:** Hourly timestamps for time-series analysis.
  
## Repository Structure

```text
├── data/            # Raw and processed datasets
├── images/          # Visualizations, plots, and project screenshots
├── notebooks/       # Jupyter Notebooks (EDA, preprocessing, and training)
├── venv/            # Python virtual environment (local setup)
├── README.md        # Main project documentation
└── requirements.txt # Project dependencies and libraries

