

# House Price Prediction Analysis

This repository contains code and analysis for predicting house prices using linear regression. The analysis involves comparing the true values of house prices with the predicted values using a scatter plot.

## Table of Contents

1. [Overview](#overview)
2. [Data](#data)
3. [Analysis](#analysis)
4. [Results](#results)

## Overview

The goal of this project is to predict house prices based on features such as total square footage, number of bedrooms, and number of bathrooms. The analysis includes:

- Data preparation
- Linear regression model training
- Evaluation of predictions

## Data

The dataset used in this analysis contains various features of houses, including square footage, number of bathrooms, and number of bedrooms. The target variable is the sale price of the house.

## Analysis

1. **Data Preparation**: 
   - Calculate the total square footage from various columns.
   - Combine the number of bathrooms into a single column.
   - Extract relevant columns for model training and testing.

2. **Model Training**:
   - Train a linear regression model using the prepared dataset.

3. **Evaluation**:
   - Compare the predicted values with the true values using a scatter plot.

## Results

The scatter plot below shows the comparison between the true house prices (`y_test`) and the predicted house prices (`y_pred`). The red dashed line represents the ideal scenario where the predicted values exactly match the true values.

![Comparison Plot](https://cdn.discordapp.com/attachments/878926518095581185/1273666269911973888/image.png?ex=66bf71a6&is=66be2026&hm=90fdb45a850b5ea6274a91dbda62e73f19ec9ea7b99816334e9fb0b67958419a&)
