# Hull Tactical Market Prediction — Timing the S&P 500 Using Machine Learning

## Overview

This project is my solution for the Hull Tactical Market competition on Kaggle.
The goal is to predict the future excess returns of the S&P 500 and convert these predictions into a daily portfolio allocation between 0 and 2, while staying within a strict volatility constraint.

The project challenges a core idea in finance:

“Markets are fully efficient and impossible to predict.”

Using machine learning, feature engineering, and walk-forward validation, I attempt to uncover patterns in the market and build a trading strategy that can outperform the S&P 500 on a risk-adjusted basis.

## Objectives

Predict market_forward_excess_returns using the provided features (D*, E*, I*, M*, P*, S*, V*).

Build a robust, leak-free time-series pipeline.

Convert predictions into a daily leverage allocation between 0 and 2.

Respect a 120% volatility limit relative to the market.

Simulate and evaluate performance using the competition’s custom Sharpe-style metric.

## Dataset

The training data includes:

~9,000 daily observations

90+ engineered features grouped into:

D* (Daily Indicators)

E* (Economic/Proprietary Signals)

I* (Volatility/Implied Indicators)

M* (Momentum Features)

P* (Price/Market Structure)

S* (Statistical Factors)

V* (Volatility Windows)

## Target:

market_forward_excess_returns
Inputs also include:

forward_returns

risk_free_rate


## Kaggle notebook environment


## Results (updates):

The goal of the system is to generate:

Smooth leverage allocations (0–2)

Improved risk-adjusted returns vs. benchmark

Consistent out-of-sample performance

Strong leaderboard performance during the evaluation phase

## (Results will be updated as the project progresse)
