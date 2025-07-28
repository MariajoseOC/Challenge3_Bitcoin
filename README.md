# 🪙 Bitcoin Price Prediction Using Machine Learning

This repository contains a KNIME-based machine learning workflow to predict Bitcoin prices using 30-minute interval data. The workflow includes data preprocessing, feature analysis, and predictive modeling using Polynomial Regression and Random Forest Regressor.

## 📌 Project Overview

- **Objective**: Predict the price of Bitcoin using past 30-minute price data.
- **Tools Used**: [KNIME Analytics Platform](https://www.knime.com/)
- **Algorithms**:
  - Polynomial Regression
  - Random Forest Regression

## 🧠 Workflow Summary

![Workflow Diagram](images/workflow-diagram.png)

### Steps in the Workflow:
1. **Data Reading**: Load the CSV dataset containing 30-minute Bitcoin prices.
2. **Preprocessing**:
   - Handle missing values
   - Normalize features
   - Convert numeric features to string where needed
3. **Exploratory Analysis**:
   - Box plots
   - Linear correlation
4. **Model Training**:
   - Train Polynomial Regression and Random Forest Regression models
   - Evaluate using Numeric Scorer
5. **Visualization**:
   - Scatter plots, line plots, and heatmaps for prediction results

## 📁 Repository Structure

