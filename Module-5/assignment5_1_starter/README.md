# Assignment 5.1: Coupon Acceptance Analysis

This assignment analyzes the `coupons.csv` dataset to identify factors that affect whether a driver accepts a coupon.

## Summary of Findings

- The dataset contains coupon scenarios, including user demographics, travel context, weather, time, and coupon type.
- The overall coupon acceptance rate is approximately **56.84%**.
- The `car` column contains only missing values and was dropped from the analysis.
- Duplicate rows were removed before exploratory analysis.
- Temperature Histogram: The temperature values appear in discrete categories rather than a continuous spread, suggesting temperature behaves like a categorical feature.
- Temperature Count Plot: `55F` is the dominant temperature value, with fewer examples at `30F` and `80F`, indicating the dataset is weighted toward moderate weather.
- Younger drivers (under 30) are more responsive to bar related promotions.

## What this notebook covers

- Loading and inspecting the dataset
- Checking for missing or problematic data
- Handling sparse or irrelevant columns
- Calculating coupon acceptance proportions
- Visualizing coupon-type distribution
- Examining temperature distribution

## Link to notebook

Open the detailed analysis in the notebook:

- [prompt.ipynb](prompt.ipynb)

## File locations

- Notebook: `prompt.ipynb`
- Data: `data/coupons.csv`
