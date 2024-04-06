# Overview

In this project, the objective is to predict the price of the **S&P500** stock market index based on historical closing prices 

## Learning Objectives

The following points were the objectives of the project. The main intention was to create an ML model with the potential to improve accuracy, to help make decisions about investing in the stock market
- Data Gathering
- Data Visualizations
- Data Preprocessing
- Data Modelling
- Model Evaluation
- Model Deployment

## Project Steps

1. Import the Yahoo Finance package, yfinance, to download financial data
2. After cleaning the data, train an initial machine learning model and measure accuracy
3. Build a Backtesting system to acurately measure errors over long periods of time
4. Improve the model by adding predictors

## Code
The code for the project can be found [here](market_predictor/sp500_predictor.ipynb)

The code with additional comments describing the purpose of each step can be found [here](market_predictor/sp500_predictor_with_comments.ipynb)

# Local Setup

## Installation
To execute this program locally, install the following:
- JupyterLab
- Python 3.8+
- Python packages:
    - pandas
    - yfinance
    - scikit-learn

 ### Data
 All of the data during the project will be dowloaded using the yfinance package. 

 # Next Steps   

There are several other predictors that can be added to futher improve the accuracy of this model. Some predictors that can be implemented include:
- News articles about the S&P500
- Macroeconomic coniditons such as inflation, interest rates, etc.
- Key components of the S&P500 such as key stocks, key sectors, etc.

In addition, we can increase the resolution. In this model we investigated the data on a daily basis, but we may also investigate the data by hour, minutes, etc.

In conclusion, there are countless different ways to improve the accuracy of this model as the next steps in this project.

# Credits
A full walkthrough of the creation of this project can be found [here](https://youtu.be/1O_BenficgE?si=pPSiTyJhxNhc6dqZ) by DataQuest, including the full [overview](https://github.com/dataquestio/project-walkthroughs/blob/master/sp_500/market_prediction.ipynb).

