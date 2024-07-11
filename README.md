# CloudBurst Prediction System

## Overview
The CloudBurst Prediction System is a machine learning project designed to predict the likelihood of a cloudburst based on various weather parameters. This project utilizes a RandomForestClassifier for predictions and includes an interactive graphical user interface (GUI) built with Tkinter for user input and prediction display.

## Features
- Data preprocessing including handling missing values, encoding categorical variables, and standardizing numerical features.
- Exploratory Data Analysis (EDA) with visualizations such as count plots, correlation heatmaps, histograms, KDE plots, and box plots.
- Model training using RandomForestClassifier.
- Model evaluation using accuracy score, classification report, confusion matrix, ROC curve, and precision-recall curve.
- Risk factor analysis for different locations.
- Interactive GUI for user input and cloudburst risk prediction.

## Dataset
The dataset used for this project includes weather data with columns such as Date, Location, MinimumTemperature, MaximumTemperature, Rainfall, Evaporation, Sunshine, WindGustDirection, WindGustSpeed, WindDirection9am, WindDirection3pm, Humidity9am, Humidity3pm, Pressure9am, Pressure3pm, Cloud9am, Cloud3pm, Temperature9am, Temperature3pm, CloudBurstToday, and CloudBurstTomorrow.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/Shreya7280/CloudBurstPrediction.git
    cd CloudBurstPrediction
    ```

## Usage
1. Ensure you have the dataset file (`cloudpredictionsystemproject.csv`) in the project directory.
2. Enter the weather parameters in the GUI and click "Predict" to see the cloudburst risk prediction.

## Code Structure
- `CloudBurstPredictionSystem.ipynb`: The main script to run the project.
- `cloudpredictionsystemproject.csv`: The dataset file.
  
## Exploratory Data Analysis
Several EDA visualizations are included to understand the dataset better:
- Distribution of CloudBurstTomorrow.
- Correlation Heatmap.
- Histograms and KDE plots of numerical features.
- Boxplots of numerical features.

## Model Training and Evaluation
The model is trained using RandomForestClassifier with the following steps:
1. Data preprocessing.
2. Feature engineering.
3. Model training and evaluation.
4. Visualization of feature importances, confusion matrix, ROC curve, and precision-recall curve.

## GUI for Prediction
An interactive Tkinter-based GUI allows users to input weather parameters and receive cloudburst risk predictions. The GUI includes fields for Minimum Temperature, Rainfall, Sunshine, WindGustSpeed, Humidity, Cloud, Location, and CloudBurst Today.

