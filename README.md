# 🌫️ Air Pollution Prediction using Gradient Boosting Machine

[![Python](https://img.shields.io/badge/Python-3.13%2B-blue.svg)](https://www.python.org/)
[![Framework](https://img.shields.io/badge/Model-LightGBM-orange.svg)](https://lightgbm.readthedocs.io/)

## Overview
This project builds a **Gradient Boosting Machine (GBM)** model to predict atmospheric pollutant concentrations (e.g., $CO$, $NO_2$, $PM_{2.5}$) based on historical air quality sensor readings.

## Features
- **Data Preprocessing:** Automated cleaning, outlier detection, and missing value imputation.
- **Feature Engineering:** Temporal features (hour, day, month) and rolling averages.
- **Model Training:** Hyperparameter tuning using LightGBM / Scikit-Learn.
- **Evaluation:** Visual and statistical comparison between actual vs. predicted values.

## Dataset
This project utilizes the **[Air Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Air+Quality)** from the UCI Machine Learning Repository, containing hourly response responses from an array of 5 metal oxide chemical sensors.

## Repository Structure
```text
├── images/          # Visualizaciones, gráficos y capturas del proyecto
├── notebooks/       # Jupyter Notebooks (EDA, limpieza y entrenamiento)
├── README.md        # Documentación principal del proyecto
└── requirements.txt # Dependencias y librerías necesarias


