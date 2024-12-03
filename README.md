# Weather Forecasting Using Explainable AI (XAI)

This project leverages Explainable AI (XAI) techniques with advanced machine learning models, specifically Long Short-Term Memory (LSTM) networks, to create an accurate and interpretable weather forecasting system. The project integrates tools like SHAP to provide insights into the factors influencing predictions.

---

## Table of Contents
1. [Overview](#overview)
2. [Features](#features)
3. [Dataset](#dataset)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Future Work](#future-work)
9. [Authors](#authors)
10. [License](#license)

---

## Overview

Weather forecasting is essential for decision-making in agriculture, disaster management, and more. This project aims to improve forecasting accuracy while addressing the interpretability challenges of AI models by using SHAP and LIME for feature analysis.

---

## Features

- **Multi-step forecasting** of key weather parameters like temperature, humidity, and precipitation.
- **Explainability** using SHAP values to analyze feature contributions.
- **LSTM-based architecture** for capturing temporal dependencies in weather data.
- **Visualizations** of model performance, including:
  - Training vs. Validation Loss
  - Actual vs. Predicted Temperatures
  - Regional Error Analysis (Heatmaps)
  - SHAP value visualizations for test samples

---

## Dataset

The dataset used provides comprehensive weather data for major Indian cities, starting from August 29, 2023. Key features include:
- Temperature, Humidity, Wind Speed, Precipitation
- Air Quality Parameters (PM2.5, PM10, Ozone)

Preprocessing steps include handling missing values, normalization, and feature selection.

---

## Methodology

1. **Data Preprocessing**:
   - Cleaning, normalization, and feature selection.
   - Dimensionality reduction using PCA.

2. **Model Development**:
   - LSTM-based sequence-to-sequence model.
   - Optimized with Adam optimizer and MSE loss function.

3. **Explainability**:
   - SHAP and LIME for feature contribution analysis.

4. **Evaluation**:
   - Performance measured using RMSE, MAE, and visualization tools.

---

## Results

- The model achieved low error rates for temperature and humidity predictions.
- Explainability analysis provided insights into the influence of key features:
  - Humidity and temperature were the most impactful.
- Heatmaps revealed regional performance differences.

### Visualizations:
1. Training vs. Validation Loss Curve
2. Actual vs. Predicted Temperature Curve
3. Regional Error Analysis Heatmaps
4. SHAP Value Visualizations for Individual Predictions

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Jupyter Notebook

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/username/weather-forecasting-xai.git
   cd weather-forecasting-xai
