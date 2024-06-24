![1_AO2rIhzRYzFVQlFLx9DM9A](https://github.com/VIS172/Handwritten_Digit_Classification/assets/109724129/2a645865-3cc5-4db0-9b60-9a3da0c663b3)

# Handwritten Digit Classification using ANN 

This repository contains code for building and training an Artificial Neural Network (ANN) to classify handwritten digits from the MNIST dataset.

## Overview

The MNIST dataset contains 60,000 training images and 10,000 testing images of handwritten digits (0-9), each of size 28x28 pixels. The goal is to create a model that can accurately classify these digits.

## Model Architecture

The model is a simple feedforward neural network with the following architecture:
- Input Layer: Flattening the 28x28 images into a 784-dimensional vector.
- Hidden Layer: Dense layer with 128 neurons and ReLU activation.
- Output Layer: Dense layer with 10 neurons (one for each digit) and Softmax activation.

## Requirements

- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib

## Results
   The model achieves a test accuracy of approximately 98%. Further improvements can be made by tuning hyperparameters, using more advanced architectures, or applying techniques like data augmentation.

## Acknowledgments
  The MNIST dataset is provided by Yann LeCun and can be found at http://yann.lecun.com/exdb/mnist/.

  
  This project is built using Keras and TensorFlow.

You can install the required packages using pip:

```sh
pip install tensorflow keras numpy matplotlib




