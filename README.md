# Gomycode-Project

Bike Ride Demand Forecasting using Machine Learning

## Project Overview

This project aims to forecast hourly bike ride demand using historical data from the London bike-sharing dataset. The predictions help optimize fleet management for bike-sharing platforms such as Ola.

** Dataset**

Source: London Bike Sharing Dataset

Features:

timestamp, t1 (temperature), hum (humidity), wind_speed

season, is_weekend

cnt: number of ride requests (target variable)

Tech Stack

Python

pandas, numpy

matplotlib, seaborn

scikit-learn

Streamlit (for deployment)



 **Machine Learning Workflow**

Data Cleaning & EDA

Handled missing values and anomalies

Visualized demand trends by hour, day, and season

Feature Engineering

Extracted hour, day, and month from timestamps

Applied K-means clustering to group similar demand conditions

Model Building

Trained and compared: Linear Regression, Random Forest, Gradient Boosting

Used RMSE and R² as evaluation metrics

Best model: Random Forest Regressor

Deployment (Optional)

Developed a Streamlit app for interactive prediction
