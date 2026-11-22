# EV Range Prediction Under Delhi Conditions

A hybrid physics + machine-learning model that predicts the real-world driving range of an
electric car under Delhi's heat and traffic, and compares it with the certified (MIDC) range.

## How to run
Click to open in Google Colab, then choose Runtime → Run all (about 10 minutes):
https://colab.research.google.com/github/your-github-username/ev-range-delhi/blob/main/EV_Range_Delhi.ipynb

No setup needed: the dataset is in `data/` and is downloaded automatically.

## Models
Physics model, Linear Regression, Random Forest, XGBoost, Hybrid Physics + Random Forest,
Hybrid Physics + XGBoost (default and tuned with RandomizedSearchCV).

## Data sources
- Vehicle Energy Dataset (VED), University of Michigan: https://github.com/gsoh/VED (Apache-2.0)
- Delhi weather: Open-Meteo historical weather API
- Modified Indian Driving Cycle (MIDC)
