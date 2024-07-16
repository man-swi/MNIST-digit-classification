# MNIST-digit-classification

This repository contains an implementation of a neural network for classifying handwritten digits using the MNIST dataset.

![photo_2024-07-13_21-08-59 ](https://github.com/user-attachments/assets/bfa3171b-e355-49df-bbb5-22d3783f0a36)


## Project Overview

The goal of this project is to build a neural network model that can accurately classify images of handwritten digits (0-9) from the MNIST dataset. The project includes the following steps:

1. Data preprocessing
2. Model architecture design
3. Model training and evaluation
4. Results visualization

## Dataset

The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits. Each image is a 28x28 pixel grayscale image.

## Model Architecture

The neural network architecture used in this project is as follows:
- Input layer: 28x28 neurons (flattened)
- Hidden layer 1: 128 neurons, ReLU activation
- Hidden layer 2: 64 neurons, ReLU activation
- Output layer: 10 neurons (one for each digit), Softmax activation

## Installation

To run the project, you need to have Python installed along with the following libraries:
- NumPy
- TensorFlow
- Matplotlib
- Seaborn

You can install the required libraries using pip:

```bash
pip install numpy tensorflow matplotlib
