# Wine Classification Using Neural Networks

## Overview
This project uses a neural network to classify wines as red or white based on their chemical properties. The dataset is sourced from the UCI Machine Learning Repository. The project involves data preprocessing, visualization, and model training to predict wine type.

## Features
- Reads and processes wine quality datasets (red and white wines).
- Visualizes the distribution of alcohol content in red and white wines.
- Builds and trains a neural network using Keras for wine classification.
- Outputs predictions based on chemical properties.

## Project Workflow

### Data Loading:
- Import datasets and perform exploratory data analysis.

### Visualization:
- Create histograms to visualize the alcohol distribution in red and white wines.

### Preprocessing:
- Add a `type` column to label wine types (`red = 1`, `white = 0`).
- Split the data into training and testing sets.

### Model Building:
- Use Keras to build a neural network with:
  - **Input layer**: 11 chemical properties.
  - **Hidden layers**: ReLU activation.
  - **Output layer**: Sigmoid activation for binary classification.

### Training and Prediction:
- Train the model and predict wine types on test data.

## Results
- The trained neural network predicts whether a wine is red or white with a high degree of accuracy.
- Visualizations provide insights into the distribution of features like alcohol content.
