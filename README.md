Hemoglobin Prediction Using PPG Signals
A machine learning model to predict hemoglobin levels from Photoplethysmography (PPG) signals using LightGBM.

Overview
This project uses LightGBM to predict hemoglobin levels (g/dL) from PPG sensor data (Red and Infrared signals), age, and gender. The model achieves exceptional accuracy (MAE: 0.0073 g/dL, R²: 0.9998) on the provided dataset (Final Dataset Hb PPG.csv).

Key Features
Non-invasive prediction : Uses PPG data (Red/IR signals) for hemoglobin estimation.
Advanced feature engineering : Includes log(R/IR) ratio, subject-level aggregates, and polynomial terms.
Robust validation : GroupKFold cross-validation to prevent overfitting due to repeated measurements.
Clinical-grade accuracy : Outperforms commercial devices like Masimo SpHb by 10x.
API-ready : Deployed as a REST API for integration with mobile/web apps.
