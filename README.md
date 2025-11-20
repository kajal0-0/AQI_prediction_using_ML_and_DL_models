# AQI_prediction_using_ML_and_DL_models
Built a deep learning framework using multiple ML and DL models to predict Air Quality Index (AQI) trends. Hyperparameters were fine-tuned to improve model accuracy and reduce overfitting. The project uses government-certified AQI datasets to ensure reliable and practical predictions for real-world applications.

# Directory Structure:

Ablation_Studies_Base_Models/

Contains ablation studies for core individual models, including:

# CNN

# TCN

# LSTM

Inside this folder, each model has a dedicated code file containing:

- Data preprocessing steps

- Feature selection methods

- Experimental evaluations

- Individual performance comparisons

- Necessary graph plot comparisons


Hybrid_and_Ensemble_Study/

This directory contains combined model studies, including:

# Hybrid CNN-LSTM Model

# Hybrid TCN-LSTM Variants

Ensemble Experiments, including:

# XGBoost + TCN-LSTM

# CatBoost + TCN-LSTM (Final recommended model)

Note: The TCN-LSTM hybrid experiments and ensemble model results are documented in the same file for easier comparative evaluation.


## License

© 2025 Sonali P. Sunny and Kajal Pahil. All rights reserved.  
This repository is not open-source. Unauthorized use, copying, or distribution is prohibited.
