# Anemia Severity Predictor (WHO‑based)

A simple machine learning app that predicts anemia severity from complete blood count (CBC) features and a diet‑risk proxy, using WHO‑based hemoglobin thresholds.

## What it does

- Loads a real CBC anemia dataset.  
- Splits hemoglobin values into 4 WHO‑based classes: no_anemia, mild, moderate, severe.  
- Trains an SVM model (with Logistic Regression and XGBoost as baselines).  
- Serves predictions via a Streamlit web app with friendly, user‑oriented messages.

## Goal
Educational project - showing how to go from real clinical data → WHO‑based labels → feature engineering → model training → a simple health‑tech demo app.

## Tech Stack

 Engine:Python,Scikit-Learn
 Interface:Streamlit