# Energy Consumption Forecasting

## Project Overview

This project focuses on forecasting household energy consumption using time series analysis and machine learning techniques. The objective is to analyze historical electricity usage patterns and predict future energy consumption to support better energy management and planning.

The project includes:

* Data preprocessing and cleaning
* Exploratory Data Analysis (EDA)
* Time series resampling and visualization
* Stationarity testing using ADF Test
* Forecasting using statistical and machine learning models
* Model evaluation using performance metrics

---

# Problem Statement

Energy consumption forecasting is important for efficient energy distribution, resource planning, and reducing power wastage. This project aims to predict future household electricity usage based on historical consumption data.

By applying time series forecasting techniques, the project identifies consumption trends, seasonal patterns, and fluctuations in electricity usage.

---

# Dataset Information

### Dataset Used

Household Electric Power Consumption Dataset

### Features Used

Some important features from the dataset include:

* Global_active_power
* Global_reactive_power
* Voltage
* Global_intensity
* Sub_metering_1
* Sub_metering_2
* Sub_metering_3
* Date
* Time

---

# Technologies & Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Prophet
* Scikit-learn
* Google Colab / Jupyter Notebook

---

# Project Workflow

## 1. Environment Setup & Data Ingestion

* Imported required libraries
* Loaded dataset into the notebook
* Performed initial data inspection

## 2. Data Preprocessing & Cleaning

* Handled missing values
* Converted date and time columns into datetime format
* Set datetime as index
* Removed unnecessary columns
* Checked duplicate records

## 3. Exploratory Data Analysis (EDA)

* Visualized energy consumption patterns
* Generated bar plots and heatmaps
* Analyzed trends and seasonal behavior
* Performed temporal resampling

## 4. Statistical Analysis

* Applied ADF (Augmented Dickey-Fuller) Test
* Checked stationarity of the time series
* Performed differencing where required

## 5. Forecasting Models

### SARIMA Model

Used SARIMA for seasonal time series forecasting.

### Prophet Model

Used Facebook Prophet to capture trends and seasonality effectively.

## 6. Model Evaluation

Evaluation metrics used:

* MAE (Mean Absolute Error)
* RMSE (Root Mean Squared Error)

---

# Results

* Successfully analyzed historical energy consumption patterns.
* Built forecasting models for predicting future electricity usage.
* Compared forecasting performance using evaluation metrics.
* Prophet model showed strong performance for handling seasonality and trend patterns.

---

# Folder Structure

```bash
Energy-Consumption-Forecasting/
│
├── forecasting.ipynb
├── README.md
├── dataset/
├── images/
└── requirements.txt
```

---

# How to Run the Project

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset.
3. Run all notebook cells sequentially.
4. View visualizations, forecasting outputs, and evaluation metrics.

---

# Future Improvements

* Implement deep learning models like LSTM using PyTorch.
* Deploy the forecasting model using Streamlit.
* Add real-time forecasting dashboard.
* Improve hyperparameter tuning for better accuracy.

---

# Key Learnings

* Time series preprocessing techniques
* Stationarity and differencing concepts
* Seasonal forecasting methods
* Forecast evaluation techniques
* Practical implementation of Prophet and SARIMA models

---

# Conclusion

This project demonstrates how time series forecasting techniques can be applied to predict household energy consumption effectively. The implementation of SARIMA and Prophet models helps understand energy usage patterns and supports better decision-making for energy management.

---
## Project Demo Video
YouTube Demo Link: <https://youtu.be/wJ8G6OCGK7s?si=iE2nWGpvJOdBoIVu>

# Author

Shruti Suresh

Data Science Intern | Machine Learning & Data Analysis Enthusiast

