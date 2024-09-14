# Distributional Forex Prediction

This repository contains methods and models for predicting foreign exchange (forex) rates using distributional time series prediction. The focus is on applying advanced statistical and machine learning approaches to forecast forex rates and evaluate their predictive performance.

## Repository Structure

```plaintext
distributional-forex-prediction/
│
├── Archiv/ # Folder containing previous aproaches
│   
│
├── auto_gluon/ # Folder all the autogluon weights and logs
│   ├── autogluon_model/         # weights and logs of the small models
│   ├── autogluon_model_chronos/         # Weights and logs of the chronos model
│   ├── autogluon_model_high/         #  Weights and logs of the large models
│   ├── autogluon_model_medium/          # Weights and logs of the medium models
|
|
├── data/ # Folder containing the raw and processed forex data
│   
│
├── Plots/ # Folder containing all the plots of this study
|
|
├── EURUSD_Preprocessing.ipynb # Skript containing the preprocessing of the data
| 
│
├── models.ipynb # Skript containing the implementation of the autogluon models and plotting functions
│          
│
├── strategy_analysis.ipynb # Skript evaluation of the trading strategy
|
|
├── strategy.ipynb # Skript containing the trading strategy
|
├── .gitignore               # Git ignore file
├── README.md                # Project overview and instructions
