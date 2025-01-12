# [Project 1: Valhalla Traffic Integration for Careem](https://github.com/muhammadazzazy/osm-valhalla-traffic-mapper)
## Overview
This project was implemented as part of my senior project at The American University in Cairo (AUC) with the academic advisorship of [Dr. Amr El Mougy](https://www.aucegypt.edu/fac/amr-el-mougy) and [Dr. Nouri Sakr](https://www.aucegypt.edu/fac/nouri-sakr) and the industrial advisorship of [Careem](https://www.careem.com/), the ride-hailing company. It is a Python-based solution for integrating historical traffic data with Valhalla's routing engine to improve Estimated Time of Arrival (ETA) accuracy for Careem's ride-hailing platform in Amman, Jordan. This implementation enhances Valhalla's routing capabilities without modifying its core C++ codebase to
1. Acquire accurate ETAs for validating a Random Forest Regression (RFR) model for ETA prediction.
2. Enhance the performance of the pooling algorithm by feeding it with the ETAs obtained from the Valhalla routing engine.

# [Project 2: Merchant Demand Prediction with SARIMAX](https://github.com/muhammadazzazy/osm-valhalla-traffic-mapper)
## Overview
This project was implemented as part of my senior project at The American University in Cairo (AUC) with the academic advisorship of [Dr. Amr El Mougy](https://www.aucegypt.edu/fac/amr-el-mougy) and [Dr. Nouri Sakr](https://www.aucegypt.edu/fac/nouri-sakr) and the industrial advisorship of [Careem](https://www.careem.com/), the ride-hailing company. It features a Jupyter notebook that implements time series analysis and forecasting using SARIMAX (Seasonal ARIMA with eXogenous regressors) models. The time series analysis incorporates:
- Exploratory Data Analysis (EDA) and data preprocessing
- Time series decomposition and seasonality analysis
- Model parameter selection using autocorrelation function (ACF) and partial autocorrelation function (PACF)
- SARIMAX model training and forecasting
- Model evaluation using RMSE/MSE, MAE, and Theil's U-statistic
- Residual analysis and diagnostic tests

# [Project 3: Simulated Annealing Placer](https://github.com/muhammadazzazy/SimulatedAnnealingPlacer)
## Overview
A Visual Studio project written purely in C++ that implements a cell placement tool based on the simulated annealing algorithm. The SA algorithm was optimized using several data structures from the C++ 

# [Project 4: ProcLynx: The Linux Process Manager (LPM)](https://github.com/muhammadazzazy/proclynx)
## Overview
ProcLynx is a Terminal User Interface (TUI) task manager that is written in Rust and capable of performing the following:
- killing Linux processes by name and ID
- displaying process table showing the process ID, name, percentage memory utilization, and percentage processor utilization
- showing GPU temperatures, system information, processor information, disk temperatures, and component information
