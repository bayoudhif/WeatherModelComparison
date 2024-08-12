# Comparative Weather Forecasting Models

This repository contains the implementation and comparison of three machine learning models—Linear Regression, Random Forest, and Neural Network Regressor—aimed at enhancing the accuracy of temperature forecasts. The project utilizes 2023 and 2024 weather forecast data to predict temperature at a specific location, with a focus on evaluating the performance of different modeling approaches.

## Project Overview

The objective of this project is to develop, train, and compare the effectiveness of various machine learning models in predicting temperature. The models are trained on medium-range ensemble forecast data from the European Centre for Medium-Range Weather Forecasts (ECMWF) and validated against actual temperature measurements from the VLINDER station Vlinder 19.

## Repository Structure

- `Dataset_2023/`: Contains the 2023 weather forecast and temperature data used for model training.
- `Dataset_2024/`: Contains the 2024 weather forecast data used for model testing and validation.
- `ForecastCorrection.ipynb`: Jupyter notebook for data processing, model training, evaluation, and forecasting correction.
- `environment.yml`: YAML file specifying the conda environment and dependencies required to run the project.

## Key Features

- **Data Preprocessing**: Includes steps for cleaning, merging, and selecting the most relevant features for accurate temperature prediction.
- **Model Development**: Implementation of three machine learning models: Linear Regression, Random Forest, and Neural Network Regressor.
- **Model Comparison**: Analysis of model performance using metrics such as Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R².
- **Quantile Forecasting**: Generation of quantile forecasts based on model predictions, formatted for submission.

## Results

The project demonstrates that the Neural Network Regressor provides the most accurate temperature predictions, closely followed by the Random Forest model, with Linear Regression showing lower accuracy.

## Future Work

- Explore advanced neural network architectures for improved forecasting accuracy.
- Validate the models on additional datasets, including data from 2024.
- Extend the analysis to multi-year datasets to assess the long-term performance of the models.

## Installation

To set up the environment and dependencies, run the following command:

```bash
conda env create -f environment.yml
### Activate the environment:
conda activate weather-forecast
```
## Usage
Run the Jupyter notebook to process the data, train the models, and generate forecasts:
```bash

jupyter notebook ForecastCorrection.ipynb
```


## Acknowledgments
Data provided by the European Centre for Medium-Range Weather Forecasts (ECMWF).
Temperature measurements from VLINDER station Vlinder 19.
