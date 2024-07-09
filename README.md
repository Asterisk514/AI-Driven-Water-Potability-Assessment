# Water Potability Prediction Using Neural Network with Keras

## Overview

This project aims to predict water potability using a neural network implemented with Keras. The model analyzes various water quality parameters to determine if the water is drinkable or not. Key techniques such as L2 regularization and dropout are implemented to enhance generalization and achieve significant accuracy in classification.

## Dataset

The dataset used contains measurements of several water quality parameters:
- pH
- Hardness
- Solids
- Chloramines
- Sulfate
- Conductivity
- Organic Carbon
- Trihalomethanes
- Turbidity

Each parameter contributes to determining the potability of water, categorized as drinkable (1) or not drinkable (0).

## Implementation Details

### Neural Network Architecture

The neural network architecture is designed using Keras:
- Input layer with appropriate dimensions for the number of features
- Hidden layers with ReLU activation
- Output layer with sigmoid activation for binary classification

### Techniques Used

- **L2 Regularization**: Implemented to reduce overfitting by penalizing large weights.
- **Dropout**: Applied to randomly ignore a fraction of units during training to prevent co-adaptation of neurons.

### Training and Evaluation

The dataset is split into training and test sets:
- Training set used to train the model.
- Test set used to evaluate model performance, including accuracy and other relevant metrics.

### Results

The model achieved significant accuracy in predicting water potability, demonstrating the effectiveness of neural networks for this classification task.

## Usage

To run the code:
1. Clone this repository.
2. Install necessary dependencies (Keras, TensorFlow, etc.).
3. Run the training script and adjust parameters as needed.
