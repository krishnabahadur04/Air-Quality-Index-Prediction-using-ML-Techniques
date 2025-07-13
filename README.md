# Air Quality Index Prediction using Machine Learning Techniques

This project implements machine learning models to predict Air Quality Index (AQI) values using historical pollution data. The implementation uses seaborn for visualizations and includes various regression models to determine the most effective approach.

## Project Overview

Air pollution is a major environmental health problem affecting everyone. This project aims to develop accurate prediction models for Air Quality Index to help:
- Alert citizens about dangerous pollution levels
- Help authorities implement timely interventions
- Support policy decisions for pollution control

## Dataset

The project uses the `AQI.csv` dataset which contains air quality measurements from various monitoring stations, including:
- Location information (country, state, city, station)
- Geographical coordinates (latitude, longitude)
- Pollutant measurements (min, max, average)
- Timestamp information

## Features

- **Data Preprocessing**: Cleaning and preparing the dataset for analysis
- **KNN Imputation**: Advanced technique for handling missing values
- **Feature Engineering**: Creating temporal and categorical features
- **Exploratory Data Analysis**: Comprehensive visualization using seaborn
- **Model Comparison**: Implementation of multiple regression algorithms
- **Performance Evaluation**: Analysis of model accuracy and effectiveness

## Models Implemented

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regression
- Gradient Boosting Regression

## Technical Implementation

### Dependencies

- Python 3.x
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn

### Files

- `AQI_Prediction_Seaborn.ipynb`: Main Jupyter notebook with the complete implementation
- `AQI.csv`: Dataset containing air quality measurements

## Results

The project compares different regression models to predict AQI values. Key findings include:
- Random Forest and Gradient Boosting models typically outperform linear models
- Feature importance analysis reveals key factors affecting air quality
- KNN imputation improves data quality and model performance

## How to Use

1. Clone this repository
2. Ensure all dependencies are installed
3. Open `AQI_Prediction.ipynb` in Jupyter Notebook or JupyterLab
4. Run the cells sequentially to reproduce the analysis

## Future Scope

- Incorporate real-time data streams for continuous prediction
- Add weather data to improve prediction accuracy
- Develop a web or mobile application for public access to predictions
- Implement time series forecasting for multi-day predictions
- Expand to more geographical locations



## Acknowledgements

- Data source: Air Quality monitoring stations
- Libraries: pandas, seaborn, scikit-learn, and other open-source tools

## Contact

For questions or feedback, please open an issue in this repository.
