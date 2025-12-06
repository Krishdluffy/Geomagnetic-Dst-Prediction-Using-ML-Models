# Geomagnetic Dst Prediction Using Machine Learning

This repository contains a machine-learning based regression model 
to forecast the Disturbance Storm Time (Dst) index using solar wind 
and geomagnetic parameters.

## Features
- Uses solar wind parameters: Scalar_B, BZ, Proton Density
- Uses geomagnetic indices: Kp, ap
- Predicts Dst using ML regression
- Compares 4 models:
  - Linear Regression
  - Extra Trees Regressor
  - Gradient Boosting Regressor
  - XGBoost Regressor
- Produces plots:
  - Feature Importance
  - Correlation Heatmap
  - Actual vs Predicted Dst
  - Residual Distribution
  - Residuals vs Predicted

## Repository Structure
- `/src` – main Python scripts
- `/notebooks` – Jupyter notebook version
- `/figures` – saved output plots
- `/data` – dataset (not included)
- `/models` – trained model files (optional)

## Dataset
The dataset should contain:
YEAR, DOY, Hour, Scalar_B_nT, BZ_nT, SW_Proton_Density, Kp_index, Dst_index, ap_index

Place your CSV inside `/data/omni.csv`.

## How to Run
