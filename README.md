# Forecasting Electricity Power Consumption

This repository contains code and notebooks related to forecasting electricity power consumption using time series analysis.

## Table of Contents

- [Introduction](#introduction)
- [Folder Structure](#folder-structure)
- [Models](#models)
- [Contributing](#contributing)
- [License](#license)

## Introduction

In this project, we aim to forecast electricity power consumption using various time series analysis techniques. The dataset used for analysis is not included in this repository. 

## Folder Structure

- **DataAnalysis**: Contains notebooks related to exploratory data analysis.
  - [Exploratory_Data_Analysis.ipynb](DataAnalysis/Exploratory_Data_Analysis.ipynb): Notebook for exploring the dataset.

- **Modelling**: Contains notebooks related to different forecasting models.
  - [EDA+Univariate SARIMAX.ipynb](Modelling/EDA+UnivariateSARIMAX.ipynb): Notebook for EDA and Univariate SARIMAX model.
  - [Modelling_LSTM.ipynb](Modelling/Modelling_LSTM.ipynb): Notebook for LSTM model.
  - [Multivariate_SARIMAX.ipynb](Modelling/Multivariate_SARIMAX.ipynb): Notebook for Multivariate SARIMAX model.
  - [Univariate_Modelling.ipynb](Modelling/Univariate_Modelling.ipynb): Notebook for Univariate modelling using ARIMA.
  - [VAR.ipynb](Modelling/VAR.ipynb): Notebook for VAR model.

- **PreProcessing**: Contains notebooks related to data preparation.
  - [DataPreparation.ipynb](PreProcessing/DataPreparation.ipynb): Notebook for data preparation tasks.

## Models

We utilized the following models for forecasting electricity power consumption:
- AR (Autoregressive) model
- MA (Moving Average) model
- ARIMA (Autoregressive Integrated Moving Average) model
- Multivariate SARIMAX (Seasonal Autoregressive Integrated Moving Average with Exogenous Inputs) model
- LSTM (Long Short-Term Memory) model

## Contributing

If you'd like to contribute to this project, please follow these guidelines:
- Fork the repository
- Create a new branch (`git checkout -b feature`)
- Make your changes
- Commit your changes (`git commit -am 'Add new feature'`)
- Push to the branch (`git push origin feature`)
- Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
