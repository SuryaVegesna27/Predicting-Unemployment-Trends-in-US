# Predictive Analytics Project

This repository contains code and data for a predictive analytics project focused on analyzing unemployment rates in America per US state.

## Introduction

The goal of this project is to analyze historical unemployment data, perform data preprocessing, exploratory data analysis (EDA), and build predictive models to forecast future unemployment rates. The project utilizes various techniques, including time series analysis, statistical modeling, and machine learning.

## Data

The dataset used in this project is sourced from [Unemployment in America Per US State.csv](https://www.kaggle.com/datasets/justin2028/unemployment-in-america-per-us-state/data), containing information about unemployment rates across different US states over time.

### Data Preprocessing

The data preprocessing steps include:

- Checking for null values
- Data transformation (converting object data types to integers)
- Aggregating data by summing the population and labor force for each year and month
- Calculating percentages of labor force employed and unemployed

## Exploratory Data Analysis (EDA)

The EDA phase involves:

- Visualizing box plots and histograms to analyze the distribution of unemployment rates
- Performing bivariate analysis to explore relationships between variables
- Identifying states with the highest and lowest unemployment rates

## Outlier Removal

Outliers are identified using the interquartile range (IQR) method and removed from the dataset to improve model performance.

## Time Series Analysis

Time series analysis is conducted to understand the temporal patterns in unemployment data. This includes:

- Checking stationarity using the Augmented Dickey-Fuller (ADF) test
- Plotting autocorrelation and partial autocorrelation functions
- Building ARIMA models for forecasting future unemployment rates

## LSTM Model

A Long Short-Term Memory (LSTM) model is implemented to predict future unemployment rates based on historical data. The model architecture includes LSTM layers followed by dense layers for regression.

## Files

- [Unemployment in America Per US State.csv](https://github.com/Nithya-15/Predictive-Analytics/blob/main/Unemployment%20in%20America%20Per%20US%20State.csv): Raw dataset
- [Predictive Analytics - Project.ipynb](https://github.com/Nithya-15/Predictive-Analytics/blob/main/Predictive_Analytics_Project.ipynb): Jupyter Notebook containing the project code
- [README.md](README.md): Documentation providing an overview of the project

## Requirements

- Python 3
- Libraries: pandas, numpy, matplotlib, seaborn, statsmodels, scikit-learn, keras

## Usage

1. Clone the repository:
git clone https://github.com/Nithya-15/predictive-analytics-project.git

2. Navigate to the project directory:
cd predictive-analytics-project

3. Run the Jupyter Notebook:
jupyter notebook Predictive_Analytics_Project.ipynb

4. Follow the instructions in the notebook to execute the code and analyze the data.

## Contributors

- Nithyasree Kusakula (https://github.com/Nithya-15)
- Navyamsh Gangavaram
- Yash Garg


