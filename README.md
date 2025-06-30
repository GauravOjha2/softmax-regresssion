# softmax regresssion
# Softmax Regression Example

This project demonstrates how to implement a simple softmax regression (multiclass classification) model using TensorFlow and scikit-learn. The code generates a synthetic dataset with four clusters and trains a neural network to classify the data points.

## Project Overview
- **Generates synthetic data** using `make_blobs` from scikit-learn.
- **Builds a neural network** with TensorFlow Keras for multiclass classification.
- **Trains the model** and prints prediction statistics.

## Setup Instructions

1. **Clone the repository** (if applicable):
   ```bash
   git clone <your-repo-url>
   cd <your-repo-directory>
   ```

2. **Install dependencies**:
   ```bash
   pip install numpy tensorflow scikit-learn
   ```


## What the Code Does
- **Generates 2000 data points** grouped around four centers in 2D space.
- **Builds a neural network** with two hidden layers and a softmax output layer for multiclass classification.
- **Trains the model** for 10 epochs on the synthetic data.
- **Prints the first two predicted probability vectors** and the range of predicted values.

## License
This project is provided for educational purposes.

