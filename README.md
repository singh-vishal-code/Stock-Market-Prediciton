Stock Market Prediction and Model Comparison: ANN vs LSTM

This repository presents a project that predicts stock closing prices of five major companies using two machine learning models: Artificial Neural Network (ANN) and Long Short-Term Memory (LSTM). The performance of both models is evaluated and compared using standard metrics like RMSE, MAPE, and MBE.

Project Objective

To evaluate and compare the predictive performance of ANN and LSTM models in forecasting the next-day closing prices of selected stocks using historical data and technical indicators.

Companies Analyzed

Nike (NKE)

Goldman Sachs (GS)

Johnson & Johnson (JNJ)

Pfizer Inc. (PFE)

JP Morgan and Co. (JPM)

Models Compared

Artificial Neural Network (ANN)
Feedforward model with dense layers

Used standard feature inputs like moving averages and technical indicators

Long Short-Term Memory (LSTM)
Recurrent neural network capable of learning time dependencies

Trained on sequences of historical stock data

Evaluation Metrics

RMSE (Root Mean Squared Error) – Measures average prediction error

MAPE (Mean Absolute Percentage Error) – Shows average relative error

MBE (Mean Bias Error) – Detects prediction bias (under or overestimation)

Model Results

Company	ANN (RMSE / MAPE / MBE)	LSTM (RMSE / MAPE / MBE)
Nike	3.67 / 3.21% / 1.38	2.21 / 1.94% / 0.60
Goldman Sachs	19.95 / 2.69% / -3.98	13.45 / 1.73% / -4.80
Johnson & Johnson	2.54 / 1.24% / -0.78	1.92 / 0.93% / 0.24
Pfizer Inc.	0.62 / 1.90% / 0.32	0.41 / 1.23% / 0.07
JP Morgan and Co.	8.99 / 2.55% / -2.98	5.63 / 1.70% / 1.70

Key Findings

LSTM outperformed ANN across all companies in terms of RMSE and MAPE.

LSTM's MBE values were closer to zero, indicating less bias in prediction.

Temporal sequence learning in LSTM makes it more suitable for stock forecasting tasks.

Technologies Used

Python

TensorFlow / Keras

Scikit-learn

Pandas / NumPy

Matplotlib / Plotly
