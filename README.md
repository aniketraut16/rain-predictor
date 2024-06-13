# Rain Predictor

## Overview

This repository contains a simple Machine Learning project aimed at predicting whether it will rain based on weather data. The project serves as a learning exercise to understand the end-to-end process of building an ML model.

## Project Workflow

1. **Data Collection**: The dataset was sourced from Kaggle and includes various weather features.
2. **Feature Selection**: Chose cloud cover and humidity as the key features for prediction.
3. **Data Filtering**: Cleaned and prepared the data for model training.
4. **Data Splitting**: Divided the data into training and testing sets.
5. **Data Scaling**: Scaled the training data to ensure values are between 0 and 1.
6. **Model Training**: Employed the Logistic Regression algorithm to train the model.
7. **Model Testing**: Evaluated the model, achieving an accuracy of 79%.
8. **Model Export**: Saved the trained model to a `.pkl` file.

## Repository Structure

- **data/**: Contains the `rainfall.csv` dataset.
- **notebooks/**: Includes the Jupyter notebook with detailed analysis and model training steps.
- **results/**: Holds the exported model file (`model.pkl`).

## Purpose and Future Work

The primary purpose of this project was to gain practical experience with the ML project workflow rather than to deliver a highly optimized solution. Future work will focus on understanding the rationale behind algorithm choices, improving model accuracy, and refining data preprocessing steps.
