# Collinearity Case – Apple Market Risk (OLS Model)

# Overview

This project presents a market risk analysis using an Ordinary Least Squares (OLS) regression model for Apple Inc. (AAPL) stock. While the model yields apparently strong coefficients and high statistical significance, this case study aims to demonstrate why such a model should not be trusted due to the presence of multicollinearity among its independent variables.

Multicollinearity can distort economic inference, especially in financial modeling. In financial and economic modeling, high correlation between predictors can inflate variances of the estimated coefficients, leading to unstable and unreliable results. Understanding how to detect and interpret collinearity is crucial for building robust models that support sound decision-making.

Rather than focusing on implementation details (already thoroughly explained in the companion repository MARKET_RISK-OLS_Model), this project centers on the diagnosis and interpretation of multicollinearity using statistical tools.

# Objective

To provide a clear example of how collinearity—even in models with excellent statistical metrics—can lead to misleading interpretations in market risk analysis.

# Model Specification

Dependent Variable:

Apple Inc. Stock Price (AAPL)


Independent Variables:

Dow Jones Index

Federal Reserve Interest Rates (USA)

Consumer Price Index (USA)

Key Concepts Explored

Variance Inflation Factor (VIF) to measure multicollinearity.

OLS Results interpretation.


# Python Libraries:

pandas

numpy

pandas_datareader.data

datetime

seaborn

matplotlib.pyplot

statsmodels.api

sklearn.model_selection

sklearn.metrics


# References:

Companion model: MARKET_RISK-OLS_Model

Data Sources: Yahoo Finance, FRED Economic Data


# Author:

Cristina Orozco
