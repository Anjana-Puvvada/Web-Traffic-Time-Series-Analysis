# Web Traffic Time Series Analysis

## Overview
This repository contains the final project for IST652 - Scripting for Data Analysis (Fall 2023), undertaken by Anjana Sowmya Puvvada and Srushtree Pawar. The project focuses on analyzing and forecasting web traffic patterns to manage increased internet usage during the pandemic. By leveraging time series forecasting techniques, the project aims to predict future web traffic, enabling proactive measures to prevent website crashes and downtime, thereby ensuring a seamless user experience.

## Introduction
During the pandemic, the surge in internet usage led to a substantial increase in web traffic for various websites. Effective management of this traffic is crucial for preventing crashes and ensuring continuous availability. This project employs time series analysis to predict future web traffic, helping in better traffic control and distribution decisions.

## Data Source
The web traffic data is sourced from the Kaggle API, specifically the "web-traffic-time-series-forecasting" competition dataset. The dataset contains approximately 145,000 time series, each representing daily views of different Wikipedia articles from July 1, 2015, to December 31, 2016.

## Data Exploration and Cleaning
The data exploration and cleaning process includes:
- Reading and loading the data using Pandas.
- Handling missing values by replacing them with zeroes.
- Transposing and transforming the dataset to a format suitable for time series analysis.

## Analysis and Visualization
The analysis involves:
- Examining the distribution of web traffic across different Wikipedia projects, access types, and agents.
- Visualizing trends and patterns over time to understand the dynamics of web traffic.

## Model Predictions
The project uses two main forecasting models:
1. **LSTM (Long Short-Term Memory) Model**: A type of recurrent neural network designed to learn long-term dependencies in sequence prediction problems.
2. **ARIMA (AutoRegressive Integrated Moving Average) Model**: A statistical model used for analyzing and forecasting time series data, capturing trends and seasonality.

## Results and Findings
The analysis highlights the significant web traffic trends across various Wikipedia projects and languages. The LSTM and ARIMA models provide predictions for future web traffic, aiding in making informed decisions for traffic management.

## Further Exploration
Future work includes:
- Comparing data with other sources for validation.
- Analyzing seasonal patterns and external factors influencing web traffic.
- Enhancing model explainability and interpretability.

## References
- [Kaggle Web Traffic Time Series Forecasting Competition](https://www.kaggle.com/competitions/web-traffic-time-series-forecasting/data)
- [Related Kaggle Kernels](https://www.kaggle.com/code/ganeshhalpatrao/web-traffic-time-series-forecasting#MODELS)
