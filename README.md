# Neural Network Quadrant Prediction with Visualization

This repository contains Python code for training a simple neural network to predict the quadrant of an angle. The code utilizes the TensorFlow and scikit-learn libraries for machine learning and visualization.

## Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Code Explanation](#code-explanation)
    - [Quadrant Prediction Model](#quadrant-prediction-model)
    - [Neural Network Architecture Visualization](#neural-network-architecture-visualization)

## Introduction

The purpose of this project is to demonstrate how to train a neural network to predict the quadrant of an angle based on randomly generated data. Additionally, it includes an interactive visualization of the neural network architecture using Plotly.

## Requirements

Ensure you have the following dependencies installed:

- Python 3
- NumPy
- scikit-learn
- TensorFlow
- Matplotlib
- Plotly

You can install the required packages using the following command:

```bash
pip install numpy
pip install scikit-learn
pip install tensorflow
pip install matplotlib
pip install plotly
```

Clone the repository:
```bash
git clone https://github.com/your-username/neural-network-quadrant-prediction.git
cd neural-network-quadrant-prediction
```

# Code Explanation

This will train the neural network, make a prediction for a new angle, and display the decision boundaries of the model. Additionally, it will generate an interactive visualization of the neural network architecture using Plotly.

## Quadrant Prediction Model

- The script begins by generating random angles and determining their corresponding quadrants.
- The data is then one-hot encoded and split into training and testing sets.
- A simple neural network model with one hidden layer and an output layer is created using TensorFlow's Keras API.
- The model is compiled, trained, and tested on the generated data.
- Finally, the model is used to predict the quadrant for a new angle.

## Neural Network Architecture Visualization
- The code uses Plotly to create an interactive visualization of the neural network architecture.
- Nodes (representing units) and edges (representing connections) are added to the plot.
- The resulting plot provides a clear representation of the structure of the neural network.
