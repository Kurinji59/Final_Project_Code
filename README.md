# Satellite Manoeuvre Detection — Residual-Based Anomaly Detection (XGBoost & LSTM)
This repository contains two notebooks:

1. an EDA notebook with interactive plots for visual exploration of orbital elements and manoeuvres across satellites, and

2. a refactored modelling notebook that runs a residual-based anomaly detection pipeline with XGBoost and LSTM, evaluates all configurations, plots Precision–Recall curves, and summarises results.

The goal is to detect manoeuvres by forecasting Brouwer Mean Motion (BMM) and flagging large residual spikes. Evaluation is done via PR curves, F1-score, AUC-PR, TP/FP/FN, and CPU-only runtime for fairness.
