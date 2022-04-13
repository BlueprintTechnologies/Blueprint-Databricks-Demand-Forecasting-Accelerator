# Blueprint Accelerator: Retail Demand Forecasting

## Background
To illustrate the impact of this accelerator, we include sample data from a specific business use case for Citibike.

Citibike is New York city’s bike share program that is owned and operated by Lyft. The bike ride share program has become very popular in NYC, due to its high population density. Given ridership growth and its documented and well-researched benefits, it’s highly crucial to accurately forecast future bike ride demand to enable Citibike to successfully meet this increasing demand.

## Overview
The Blueprint Demand Forecasting Accelerator includes all the available historical Citibike data from Oct 2013 to Feb 2022. A pair of naïve models were initially implemented to give a baseline forecasting error for comparison. The autocorrelation of the data revealed the seasonality structure of the data (daily, weekly, and yearly). This information was subsequently used to improve the model performance.

## Special Thanks
Our Blueprint accelerator builds upon an existing Databricks accelerator called “[Granular Demand Forecasting Accelerator](https://databricks.com/solutions/accelerators/demand-forecasting)”. One area where we improved upon the original accelerator was the use of autocorrelation coefficients to discover hidden pattern of periodicity in data and used those patterns to model the seasonality. Our accelerator extends the prediction period and the overall mean squared error (MSE) and Root Mean Square Error (RMSE) are improved significantly from the original solution accelerator.

*The original version of this accelerator was created as an entry for Blueprint Technologies' X-Challenge. X-Challenges are designed to provide challenges that enable Blueprinters, through technical experimentation & exploration, to participate in a broad range of strategic initiatives.*
