'''l;;;gvvggvvgvgvvgvgvgvgvgvvggggghbbbn....
# Car-Price-Prediction-Model

## Overview

This project builds a **Multiple Linear Regression** model to predict car prices using a dataset of various cars in the US market. The model will help **Geely Auto**, a Chinese automobile company, understand key factors affecting car pricing to compete in the American market.

## Objective

- Identify significant factors influencing car prices.
- Build a predictive model to understand pricing dynamics in the US market.

## Dataset

- **Source:** `CarPrice_Assignment.csv`
- **Key Variable:** `CarName` (split into car company and model; only the company name is used in the model).

## Steps

1. **Data Cleaning & Preparation**: Extract company names from `CarName`.
2. **Modeling**: Build a multiple linear regression model.
3. **Evaluation**: Use `r2_score` to evaluate the model on test data.
