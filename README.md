Satellite Manoeuvre Detection using XGBoost and LSTM
This repository contains two Jupyter notebooks for detecting satellite manoeuvres from orbital data using a residual-based anomaly detection approach.

Contents
EDA Notebook

Performs exploratory data analysis on satellite orbital elements.

Visualises manoeuvre events and trends over time.

Compares orbital elements across satellites.

Model Notebook

Implements anomaly detection using XGBoost and LSTM.

Evaluates four configurations for each model (5 or 15 lags/windows, with or without differencing).

Calculates metrics: precision, recall, F1-score, AUC-PR.

Measures computational time on CPU for both models for fairness.

Generates precision–recall curves and summary tables.
