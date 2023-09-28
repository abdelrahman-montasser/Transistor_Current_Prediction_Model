# Transistor Current Prediction Model
This deep learning model is designed to predict the current of transistors based on several input parameters


## Table of Contents

- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Installation Instructions](#installation-instructions)
- [Data Preparation](#data-preparation)
- [Model Architecture](#model-architecture)
- [Training Process](#training-process)
- [Model Evaluation](#model-evaluation)


## Project Overview

This deep learning model is designed to predict the current of MOS transistors based on various parameters. The goal is to optimize for minimum mean absolute percentage error (MAPE) for Id (current).


## Project Structure

The project is structured as follows:


- `/models`: Stores trained machine learning models.
- `/notebooks`: Jupyter notebook for model development.
- `requirements.txt`: Project dependencies.
- `README.md`: Project introduction and instructions.

## Installation Instructions

To set up the project environment, follow these steps:

1. Clone this repository: `git clone https://github.com/abdelrahman-montasser/Transistor_Current_Prediction_Model.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Open the notebook and Run the cells
## Data Preparation

- Data sources: [Link to the data](https://drive.google.com/file/d/1F-MZMnizMAHXHRdPeh2v2Y85f7OkZCWG/view?usp=sharing)


## Model Architecture

We employ a Deep neural network with multiple layers for predicting MOS transistor current. The architecture includes:

- Input layer
- Hidden layers with ReLU activation
- Output layer with ReLU activation

## Training Process

- Hyperparameters: ur model uses a learning rate of 0.001, a batch size of 128, a maximum of 300 training epochs, dropout with a rate of 0.2, and other architecture-specific hyperparameters for MOS transistor 
 current prediction.
- Optimization: Adam optimizer
- Loss function: Mean squared error (MSE)

## Model Evaluation

- Metrics: Mean absolute error (MAE)


## Usage Examples

Here are examples of how to use the trained model for predictions:

1. Load the model.
2. Prepare input data.
3. Make predictions using the model.


