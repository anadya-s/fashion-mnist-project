# Fashion MNIST Classification with NumPy and TensorFlow

## Project Overview

This project is a deep dive into building and training a neural network for image classification on the Fashion MNIST dataset. The primary goal was to demonstrate a fundamental understanding of neural network mechanics by first building a model from scratch using only NumPy, and then building an equivalent, optimized model using TensorFlow/Keras.

This project showcases the entire machine learning workflow, from data preprocessing and model building to advanced optimization and regularization techniques.

## Part 1: Neural Network from Scratch with NumPy

I built a multi-layer neural network from the ground up to understand the core concepts:
* Forward and Backward Propagation
* Activation Functions (ReLU and Softmax)
* Cross-Entropy Loss
* Mini-Batch Gradient Descent with advanced optimizers like Adam.
* Regularization techniques like L2 Regularization.

## Part 2: Efficient Model Building with TensorFlow/Keras

To demonstrate practical, industry-standard skills, I then built an equivalent model using the Keras API in TensorFlow. This part of the project highlights:
* Rapid prototyping with the `tf.keras.Sequential` API.
* Implementing Dropout and L2 Regularization to combat overfitting.
* Evaluating model performance using validation data and plotting learning curves.

## Key Results and Visualizations

The Adam optimizer provided the best performance, achieving **88.46% test accuracy**. The project includes several key visualizations to demonstrate and compare model performance.

#### Training Comparison
This plot compares the learning curves of the baseline model, a model with L2 regularization, and the final model with the Adam optimizer. Adam clearly converges much faster.


