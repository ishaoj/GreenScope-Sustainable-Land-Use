# GreenScope: Sustainable Land Use

This project focuses on predicting crop yield based on key agricultural factors such as soil quality, annual rainfall, average temperature, and fertilizer usage. It uses a synthetic dataset generated for this purpose and applies machine learning techniques, specifically Linear Regression, to build a predictive model. The project includes data generation, exploratory data analysis (EDA), model training, and evaluation.

## Project Description

The goal of this project is to develop a model that predicts crop yield (in tons per hectare) based on four primary factors:
- Soil Quality
- Annual Rainfall (mm)
- Average Temperature (°C)
- Fertilizer Used (kg/ha)

A synthetic dataset with 5000 samples was generated, and the data was then analyzed using various exploratory techniques, such as correlation matrices, distribution plots, and scatter plots. After preparing the data (including feature scaling), a Linear Regression model was trained, achieving a strong performance with an R² score of 95.96%.

## Features
- Data Generation: A synthetic dataset with 5000 samples based on agricultural factors.
- Exploratory Data Analysis (EDA): Visualizations and correlation analysis to understand the relationships between variables.
- Linear Regression Model: Predicts crop yield using key agricultural factors.
- Model Evaluation: Includes performance metrics like Mean Squared Error (MSE) and R² score.
- Feature Importance: Visualizes the impact of each feature on the yield prediction.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/crop-yield-prediction.git
