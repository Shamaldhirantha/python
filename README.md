# Power Plant Efficiency Prediction

## Overview

This repository contains code and analysis for predicting power plant efficiency based on ambient conditions using a multiple regression model.

## Coefficients and Interpretation

The regression model was constructed using Ordinary Least Squares (OLS), and the following coefficients were obtained:

- **Intercept (`const`):** 454.6093
  - The estimated value of the dependent variable (PE) when all independent variables are zero.

- **Ambient Temperature (`AT`):** -1.9775
  - For each unit increase in Ambient Temperature, the estimated change in the dependent variable (PE) is -1.9775.

- **Exhaust Vacuum (`V`):** -0.2339
  - For each unit increase in Exhaust Vacuum, the estimated change in the dependent variable (PE) is -0.2339.

- **Ambient Pressure (`AP`):** 0.0621
  - For each unit increase in Ambient Pressure, the estimated change in the dependent variable (PE) is 0.0621.

- **Relative Humidity (`RH`):** -0.1581
  - For each unit increase in Relative Humidity, the estimated change in the dependent variable (PE) is -0.1581.

## Model Evaluation

The model's performance was assessed using key metrics:

- **R-squared:** 0.929
  - Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

- **P-values:** All coefficients have p-values less than 0.05, suggesting that they are statistically significant.



Feel free to explore and contribute to this project! For more details, refer to the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant).
