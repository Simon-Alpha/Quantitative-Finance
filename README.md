# Stochastic Volatility Surface Modeling & Heston Calibration

## Project Overview
This project implements a complete quantitative research pipeline to analyze, visualize, and model the equity options volatility surface. Using live options data, the project highlights the empirical failures of the classic Black-Scholes model (the "Volatility Smile") and implements a 2-factor Heston Stochastic Volatility Model to resolve the pricing discrepancies.

## Core Features
- **Dynamic Ingestion:** Automated scraping of live option chains using `yfinance`.
- **Surface Visualization:** Multi-dimensional plotting of 2D implied volatility smiles and 3D volatility surfaces via `matplotlib`.
- **Advanced Pricing Engine:** Implementation of the Heston model utilizing Fourier inversion techniques and numerical integration via `scipy.integrate`.
- **Model Calibration:** Non-linear optimization utilizing the Nelder-Mead algorithm (`scipy.optimize`) to fit mathematical parameters ($\kappa, \theta, \sigma, \rho, v_0$) to real market data.

## Mathematical Toolkit
- Stochastic Differential Equations (SDEs)
- Characteristic Functions & Fourier Transforms
- Continuous-time Markov Processes
