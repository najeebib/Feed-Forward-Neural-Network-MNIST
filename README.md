# MNIST Digit Classification Neural Network
## Overview
This repository contains a simple neural network implemented in PyTorch for the task of classifying handwritten digits from the MNIST dataset.

## Data
The MNIST dataset consists of 28x28 pixel grayscale images of handwritten digits (0 to 9). It is a widely-used dataset for benchmarking machine learning models.   

## Model Architecture
The neural network architecture consists of three fully connected layers:   

1 - Input layer (784 neurons): Flattened representation of the 28x28 pixel images.   
2 - Hidden layer (400 neurons): Utilizes the ReLU activation function.   
3 - Output layer (10 neurons): Represents the 10 possible digit classes.   

## Training   
The model is trained for 10 epochs with a batch size of 100. The Adam optimizer is used with a learning rate of 0.001, and the Cross Entropy Loss is employed as the loss function.   

## GPU Support
The code checks for the availability of a CUDA-compatible GPU and moves the model to the GPU if present.

## Evaluation
After training, the model is evaluated on the test set. The accuracy of the model on 10,000 test images is calculated, providing a performance metric for the trained model.

## Results
The script prints the accuracy of the trained model on the test set, giving an indication of its performance in classifying unseen handwritten digits.


