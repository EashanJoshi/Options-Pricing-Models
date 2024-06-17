# Options-Pricing-Models

Advanced Option Pricing Models
This project demonstrates the implementation of advanced option pricing models for European and American call options, incorporating real-time market data integration, sensitivity analysis, and machine learning predictions. The project is developed in Python and is aimed at providing a comprehensive tool for quantitative finance applications.

Features:

Black-Scholes Model: Pricing European call options.

Binomial Tree Model: Pricing American call options.

Real-Time Data Integration: Fetching live market data from Yahoo Finance.

Monte Carlo Simulations: Validating model accuracy and enhancing dynamic pricing.

Sensitivity Analysis: Analyzing the impact of market variables on option prices.

Implied Volatility Surfaces: Generating and visualizing volatility structures.

Machine Learning Predictions: Predicting volatility smirks and smiles using ML algorithms.

User-Interactive Python Application: Allowing selection between European and American options for analysis.

Usage:

Run the main script

Input: When prompted, enter the stock tickers separated by commas and select the option type (european/american).

Example-

Enter tickers separated by commas: GOOGL, AAPL

Enter option type (european/american): american


Main Functions:

Black-Scholes Model: Used for pricing European call options.

Binomial Tree Model: Used for pricing American call options.

fetch_market_data(ticker): Fetches the latest market data for the given ticker.

sensitivity_analysis(S, K, T, r, sigma, ticker, option_type): Conducts sensitivity analysis for the given option type.

plot_implied_volatility_surface(S, K_list, T_list, r, market_prices, ticker, option_type): Generates and plots implied volatility surfaces.

generate_market_prices(S, K_list, T_list, r, option_type): Generates market prices for the given option type.
