# Weather Forecasting with Deep Learning
### Description
This repository contains the implementation of a time series forecasting model for weather prediction, developed as part of Challenge 2 for the Deep Learning course in the Data Science master's program at the University of Padua (UNIPD).

The project focuses on predicting weather variables for 422 stations over a 30-day horizon using historical daily observations. The deep learning model processes time series data to forecast 76 weather variables simultaneously across all stations.

### Key Features
Time Series Processing: Tools for preparing and transforming multi-dimensional weather data
Deep Learning Models: Implementation of custom neural network architectures for time series forecasting
Training Pipeline: Complete workflow from data loading to model optimization
Prediction Generation: Scripts to generate forecasts and format them for evaluation

### Dataset
The project works with a dataset containing:

422 weather stations
Multiple days of historical observations
76 weather variables per day per station

### Repository Structure
dl_challenge2/
├── data/                     # Data directory
│   ├── train_dataset.csv     # Training data
│   └── submission.csv        # Generated predictions
├── models/                   # Model implementations
│   ├── __init__.py
│   └── forecaster.py         # Main forecasting model
├── utils/                    # Utility functions
│   ├── __init__.py
│   ├── dataset.py            # Dataset preparation
│   └── evaluation.py         # Model evaluation helpers
├── notebooks/                # Jupyter notebooks
│   └── DL_Challenge2_template.ipynb  # Main development notebook
├── train.py                  # Training script
├── predict.py                # Prediction generation script
├── pyproject.toml            # Project dependencies
└── README.md                 # Project documentation

### Usage
The repository provides functionalities for training weather forecasting models and generating predictions for future time steps in the required format for evaluation.

### Technologies
- PyTorch (or other deep learning framework)
- Python data science stack (Pandas, NumPy)
- Poetry for dependency management

This project was developed for the 2025 Deep Learning course at UNIPD.