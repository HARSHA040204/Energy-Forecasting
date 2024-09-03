# Electricity Production Forecasting in Romania and Turkey

## Overview

Effective forecasting of electricity production is essential for managing energy resources, ensuring grid stability, and making informed decisions in the energy sector. With the rising global demand for energy and the shift towards renewable sources, precise forecasting has become increasingly crucial. This project evaluates and compares the performance of various machine learning models to predict hourly energy production in Romania and Turkey. It explores the challenges posed by renewable energy variability, rapid economic growth, and market volatility, aiming to provide accurate and reliable forecasting tools. By analyzing these models, the project offers insights into their strengths and limitations, helping stakeholders select the most effective approach for their specific forecasting needs.

## Purpose

The primary goal of this project is to develop and compare various machine learning models for forecasting energy production in Romania and Turkey. By evaluating the performance of LSTM, XGBoost, and Random Forest models, we aim to identify the most effective approach for each country's unique energy context and provide valuable guidance for future energy forecasting applications.

## Dataset

- **Romania:** Hourly Electricity Consumption and Production data spanning five years, covering energy types such as nuclear, wind, hydroelectric, oil and gas, coal, solar, and biomass. [Link to Dataset](https://www.kaggle.com/datasets/stefancomanita/hourly-electricity-consumption-and-production)
- **Turkey:** Hourly Energy Data from January 1, 2018, to December 31, 2023, including consumption and production details across different energy sources. [Link to Dataset](https://www.kaggle.com/datasets/ahmetzamanis/energy-consumption-and-pricing-trkiye-2018-2023)

For a detailed walkthrough of our analysis, please refer to our [Colab Notebook](https://colab.research.google.com/drive/17vtI595vjk-2lM31nkHC882MbakxMzQe?usp=sharing).

## Impact

This project provides actionable insights for energy producers, policymakers, and grid operators by enhancing the accuracy of short-term energy production forecasts. Improved forecasting can lead to better resource planning, increased grid stability, and more informed policy decisions, ultimately contributing to a more efficient and sustainable energy sector.

## Key Features

- **Time Series Forecasting:** Predicts future energy production based on historical data and observed patterns.
- **Deep Learning:** Utilizes LSTM networks to capture complex time dependencies and non-linear relationships.
- **Ensemble Learning:** Applies Random Forest and XGBoost models to aggregate predictions and improve accuracy.
- **Model Evaluation:** Uses metrics such as RMSE, MAE, and R-squared to assess model performance and reliability.

## Requirements

- **Python Programming Language**
- **Libraries:**
  - Pandas, NumPy, Scikit-learn, XGBoost, TensorFlow, Keras, Matplotlib, Seaborn, Prophet

To install the necessary libraries, use:
```bash
!pip install pandas numpy scikit-learn xgboost tensorflow keras matplotlib seaborn prophet
```

## Team

- **Anish Borkar**
- **D Veera Harsha Vardhan Reddy**
- **Godavarthi Sai Nikhil**

## Mentor

We extend our sincere gratitude to **Dr. Yogesh Gupta** for his invaluable guidance and support throughout this project. His mentorship has been crucial to our success.

## Contact

For inquiries, collaboration opportunities, or further information, please feel free to reach out to:

- **Email:** dveeraharshavardhanreddy@gmail.com

Thank you for exploring this project and learning about our approach to electricity production forecasting.
