# Time Series Predictive Models for Climate Data

This study evaluates the effectiveness of three time series forecasting techniques—SARIMA, RNN, and LSTM—in predicting long-term maximum temperature (TMAX) trends using historical climate data from 1980 to 2023. Utilizing the CRISP-DM methodology, we analyzed daily weather observations from the NOAA. Models were assessed using MAE, RMSE, and MAPE metrics, and visualizations were employed for comparison.

## Research Question
We investigate how SARIMA, RNN, and LSTM models compare in forecasting long-term TMAX trends. The study aims to evaluate their predictive accuracy, strengths, limitations, and handling of seasonal patterns.

## Paper Structure
- Related Work: Reviews previous research on SARIMA and deep learning models for time series forecasting.
- Data Mining Methodology: Describes the application of CRISP-DM, data preparation, and feature engineering.
- Model Rationale: Justifies the choice of SARIMA, RNN, and LSTM based on their capabilities in time series analysis.
- Experiment Setup: Details data partitioning, model development, training, and evaluation.
- Results and Evaluation: Compares model performance using MAE, RMSE, and MAPE. Includes visualizations of predictions vs. actual data.
- Conclusion and Future Work: Summarizes findings, discusses model performance, and suggests areas for future research.

## Dataset
The dataset consists of 16,040 daily weather observations from NOAA, spanning January 1, 1980, to November 30, 2023. It includes various meteorological parameters essential for time series analysis.

## Models and Performance
- SARIMA: Showed moderate accuracy with MAE = 135.58 and RMSE = 163.50. High MAPE suggests the need for refinement.
- RNN: Demonstrated consistent performance with RMSE of 46.59 (train) and 45.29 (test). Effective in capturing temporal dynamics.
- LSTM: Slightly outperformed RNN with test RMSE of 45.59 and MAPE of 74.91%, highlighting its capability in capturing long-term dependencies.
