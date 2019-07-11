# DSCI 574: Spatial and Temporal Models

Model fitting and prediction in the presence of correlation due to temporal and/or spatial association. ARIMA models and Gaussian processes.

## Assessments

Labs

| #  | Lab topic   | Due Date |
|------|-------------| -------|
| 1 | Use R to perform certain time series analyses including plots, smoothing, decomposition, computation of the sample autocorrelation function, lagging and differencing. | 2019-02-09
| 2 | Stochastic models for time series: simulation and model selection. | 2019-02-16
| 3 | Use R to select, fit and forecast based on the ARMA family of time series models. | 2019-03-02
| 4 | Explore visualization techniques for spatial data (R package gstat). Fit popular variogram models to spatial data; perform prediction using classical kriging. | 2019-03-09

Quizzes

|     | Time | Date | Location |
|-----|------|------|----------|
| 1 | 15:00 - 15:30 | 2019-02-27 | In your lab section |
| 2 | 10:00 - 10:30 | 2019-03-13 | DPM 301 |


## Lecture

| # | Date | Day | Topic | 
|---|-------------|-------------|-------------|
| 1 | 2019-02-05 | Tue | Intro to time series; Chapter 1: Exploratory techniques in time series analysis | 
| 2 | 2019-02-07 | Thur | Continuing Chapter 1: Exploratory techniques in time series analysis | 
| 3 | 2019-02-12 | Tue | Chapter 2: Stochastic models for time series | 
| 4 | 2019-02-14 | Thur | Continuing Chapter 2: Stochastic models for time series |
| 5 | 2019-02-26 | Tue | Chapter 3: Estimation and Model Fitting for Time Series | 
| 6 | 2019-02-28 | Thur | Chapter 4: Prediction for Time Series | 
| 7 | 2019-03-05 | Tue | Chapter 5: Spatial data and spatial processes | 
| 8 | 2019-03-07 | Thur | Chapter 6: Methods for spatial prediction |
 


## Course Learning Objectives

- Chapter 1: Exploratory techniques in time series analysis
  - Informally define and explain terminology used to describe time series, including trend, seasonal effects, cyclical effects, outlier and white noise. 
  - Recognize when curve–fitting may be an appropriate method for modelling a series. 
  - Describe models for seasonal variation, including additive and multiplicative models. 
  - Apply a filter (that is, a smoother) to a time series, centering if necessary. 
  - Use a filter to estimate the seasonal indices in a time series that has an additive seasonal component. 
  - Recognize the role of transformations for time series, and identify possible transformations to address certain features of    series, such as a non-constant variance and multiplicative seasonal effects. 
  - Define the sample autocorrelation function and the correlogram. 
  - Describe the behaviour of the correlogram for series that alternate, have a trend or show seasonal fluctuations. 

- Chapter 2: Stochastic models for time series
  - Define the autocovariance and autocorrelation functions for a time series model. 
  - Define and explain what it means to say that a process is (weakly) stationary. 
  - Define what is meant by a white noise process. 
  - Define a moving average process of order q, i.e., an MA(q) . 
  - Derive the mean, variance and autocovariance function of a stationary MA(q) process. 
  - Define the notion of invertibility of a process. 
  - Define an autoregressive process of order p, i.e., an AR(p) . 
  - Derive properties for an AR(1) , including the mean, variance and autocorrelation function. 
  - Define when an AR(p) is  stationary. 
  - Define an ARMA(p, q) process and state conditions when an ARMA(p, q) process is stationary and/or invertible. 

- Chapter 3: Estimation and model fitting for time series
  - Given a class of ARMA models, list the main steps for fitting a suitable model to the data.
  - Describe estimation of the mean of the process, and of its autocovariance and autocorrelation functions. Know their statistical properties.
  - Use the correlogram to decide which model from the ARMA family is suitable for the data.
  - For an AR model, describe how to select the order of the process using the partial autocorrelation function and how to fit the remaining model parameters.
  - For an MA process, be able to determine the order of the process and describe how to carry parameter estimation.
  - Use the correlogram to identify situations when an ARMA model is suitable, and use software to fit the model. 
  - Apply model-selection criteria to choose among possible models. 

- Chapter 4: Prediction for time series
  - Describe how exponential smoothing technique can be used to make forecasts for stationary time series data.
  - Outline the steps of Box-Jenkins forecasting procedure.
  - Compute Box-Jenkins forecasts using the model equation.
  - Use the MA representation of the model to construct prediction intervals for the forecasts. 


- Chapter 5: Spatial data and spatial processes
  - Use tools in R package gstat to visualize point referenced spatial data and identify its features to guide subsequent modelling. 
  - Define a spatial random field and describe its possible representation in terms of an overall spatial trend plus a process having a spatial structure. 
  - Define second-order and isotropic stationarity. 
  - Define a Gaussian random field.
  - Define a variogram and covariance function, and recognize their role as measures of dependence over space. 

- Chapter 6: Methods for spatial prediction
  - Fit popular variogram models to spatial data and explain features such as the nugget, sill and range.
  - Understand when a linear spatial predictor is appropriate. Apply classical kriging to make spatial predictions.
  - Be familiar with modern methods of spatial prediction such as Bayesian kriging. 


## Reference Material
* Shaddick, Gavin and Zidek, James V. Spatio-Temporal Methods in Environmental Epidemiology. CRC Press, 2016.
* Chatfield, Chris. The Analysis of Time Series: An Introduction. CRC Press, 2003.
