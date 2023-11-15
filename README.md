# Predictive Maintenance RUL Estimation

## Introduction
This repository contains code and resources for predicting Remaining Useful Life (RUL) of turbofan engines using machine learning and deep learning models. The dataset used is NASA's C-MAPSS Turbofan Engine Degradation Simulation dataset, specifically focusing on FD001, the least complex dataset in the series.

## Motivation
The goal is to predict the remaining operational life of an engine, allowing for proactive maintenance and resource optimization. By leveraging various machine learning and deep learning models, this project aims to enhance predictive maintenance strategies, reduce downtime, and improve overall efficiency.

## Dataset
The dataset consists of train and test trajectories for 100 engines, each with three operational settings, 21 sensor readings, and associated RUL information. The train data is used for model training, and the test data is employed to evaluate model performance. The RUL data for the test set is used for validation.

## Files
- **train_FD001.txt:** Train data without RUL for computation.
- **test_FD001.txt:** Test data without RUL.
- **RUL_FD001.txt:** RUL for test data.

## Approach
The notebook in this repository explores various machine learning and deep learning models for predicting RUL. It covers data preprocessing, model training, and evaluation. The models aim to capture the degradation patterns of the engines over time and provide accurate estimates of the remaining useful life.

## Models Explored
- Linear Regression
- ANN
- Support Vector Machine
- RNN
- Xboost

## Usage
1. Download the dataset from [NASA C-MAPSS](https://www.kaggle.com/datasets/behrad3d/nasa-cmaps).
2. Clone this repository: `git clone https://github.com/yourusername/Predictive-Maintenance-RUL-Estimation.git`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Open and run the Jupyter notebook: `Predictive_Maintenance_RUL_Estimation.ipynb`

## Results
The notebook provides insights into the performance of each model, allowing for comparison and selection of the most effective approach for RUL prediction.

