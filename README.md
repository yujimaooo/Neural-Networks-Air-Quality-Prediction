# Neural-Networks-Air-Quality-Prediction

## Overview
This repository contains the implementation of neural networks for AI-driven time series air quality prediction. Developed as part of the COMP9414 Artificial Intelligence course, this project leverages advanced neural network architectures for both classification and regression tasks using a tailored dataset from the UCI Machine Learning Repository.

The assignment focuses on two main objectives:
- **Classification Task**: Develop a neural network to predict whether the concentration of Carbon Monoxide (CO) exceeds a certain threshold based on historical air quality data.
- **Regression Task**: Build a neural network to predict the concentration of Nitrogen Oxides (NOx) using other air quality features.

## Workflow
### Data Preprocessing
- Identify variation range for input and output variables.
- Plot variables to observe overall behavior.
- Handle outliers and missing data.
- Split data for training and testing.

### Design of the Neural Network
- Select and design neural architectures for both classification and regression tasks
- Use Keras and TensorFlow for implementation

### Training
- Set training parameters: loss function, optimizer, batch size, learning rate, and epochs.
- Train the model and monitor loss values to avoid overfitting.

### Validation
- For classification: Plot training and validation loss, accuracy over epochs, compute confusion matrix, accuracy, and precision.
- For regression: Plot training and validation loss, predicted vs. actual values, compute RMSE and MAE.
