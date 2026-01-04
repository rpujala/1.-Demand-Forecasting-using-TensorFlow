# 1.-Demand-Forecasting-using-TensorFlow
This project implements a time-series demand forecasting model using TensorFlow, aimed at predicting future demand based on historical data. The solution reflects real-world supply chain planning and forecasting challenges.

**Problem Statement:**
Given historical demand data, forecast future demand to support:
  a. Inventory planning
  b. Capacity planning
  c. Supply chain optimization

**Solution Approach:**
  1. Data Preparation:
    a. Sliding window technique for sequence generation
    b. Train / validation split
    c. Feature scaling
  2. Modeling:
    a. TensorFlow Sequential API
    b. Dense / LSTM-based neural networks
    c. Loss: Mean Absolute Error (MAE)
  3. Evaluation:
    a. MAE / RMSE
    b. Visual comparison of actual vs predicted demand

**Tech Stack:**
  a. Python
  b. TensorFlow
  c. Pandas
  d. NumPy
  e. Matplotlib
  f. Scikit-learn
  g. Pipelines

**Results:**
  a. Successfully captured demand trends and seasonality patterns
  b. Demonstrated how deep learning can be applied to real-world forecasting problems

**Use Case:**
  Applicable to:
    a. Supply chain demand planning
    b. Inventory optimization
    c. Operations analytics
