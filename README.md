# Stock Market Analysis: VIX Index Prediction

This project analyzes the relationship between the Volatility Index (VIX) and various Economic Policy Uncertainty (EMV) trackers using statistical modeling techniques. The analysis aims to understand and predict stock market volatility through data-driven methodologies.

## Project Overview

The analysis focuses on:
- Understanding the relationship between VIX and EMV trackers
- Implementing various regression models to predict VIX values
- Evaluating model performance and identifying key predictors
- Providing insights into stock market volatility patterns

## Key Features

- Data preprocessing and analysis of EMV_VIX dataset
- Implementation of multiple statistical models:
  - Ordinary Least Squares (OLS) Regression
  - LASSO Regression
  - Ridge Regression
  - Elastic Net Model
- Comprehensive model evaluation and comparison
- Visualization of results and model diagnostics

## Technical Details

### Required Libraries
- tidyverse
- ggplot2
- readxl
- caret
- e1071
- glmnet
- ISLR
- car

### Data Source
The analysis uses EMV_VIX_Data.xlsx, containing:
- VIX index values
- Various EMV trackers
- Monthly data points

## Repository Structure
- `generate_report.rmd`: R Markdown file containing the complete analysis
- `report.pdf`: Final report with analysis results and visualizations

## Usage
1. Install required R packages
2. Place the EMV_VIX_Data.xlsx file in the working directory
3. Run the R Markdown file to generate the analysis report

## Results
The analysis demonstrates the ability to predict VIX values using EMV trackers, with various models showing different levels of predictive power. The report includes detailed model comparisons, diagnostic plots, and interpretation of results.
