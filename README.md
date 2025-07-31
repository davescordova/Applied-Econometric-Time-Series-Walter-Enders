# Python Implementations for "Applied Econometric Time Series"

This repository provides Python code and practical implementations for the models and examples discussed in the textbook **"Applied Econometric Time Series, 3rd Edition" by Walter Enders**.

The primary goal of this project is to serve as a hands-on companion for students, academics, and practitioners who are using the book to learn and apply time-series analysis. All code is written in Python, using libraries like `statsmodels`, `pandas`, `numpy`, `matplotlib`, and `arch`.
Also, some features in R are implemented through Python in order to install those libraries, load and run then without turning to R.

![Book Cover](https://m.media-amazon.com/images/I/81FzPYKsj2L._SX445_.jpg)

***

## Chapter Contents

The repository is organized into folders that correspond to the chapters in the book.

* ### Chapter 1: Difference Equations
    * This section covers the fundamental concepts of difference equations, their stability conditions, and the simulation of basic time-series processes.
    * As this is theoretical, it is not covered here.

* ### Chapter 2: Stationary Time-Series Models
    * Implementations of Autoregressive Moving Average ($ARMA(p, q)$) models. This includes code for model identification using the Autocorrelation Function (ACF) and Partial Autocorrelation Function (PACF), parameter estimation, and forecasting.

* ### Chapter 3: Modeling Volatility
    * Code for modeling and forecasting volatility using Autoregressive Conditional Heteroskedasticity ($ARCH$) and Generalized Autoregressive Conditional Heteroskedasticity ($GARCH$) models.

* ### Chapter 4: Models with Trend
    * Scripts for handling non-stationary time series. This includes models with deterministic and stochastic trends, as well as unit-root tests like the Augmented Dickey-Fuller (ADF) test.

* ### Chapter 5: Multiequation Time-Series Models
    * Implementation of Vector Autoregression (VAR) models. The code covers Granger causality tests, Impulse Response Functions (IRFs), and Forecast Error Variance Decomposition (FEVD).

* ### Chapter 6: Cointegration and Error-Correction Models
    * Code for cointegration analysis, including the Engle-Granger and Johansen tests, and the implementation of Vector Error Correction Models (VECM).

* ### Chapter 7: Nonlinear Time-Series Models
    * Implementations of advanced nonlinear models, such as Threshold Autoregressive (TAR) and Markov Switching models.

***


