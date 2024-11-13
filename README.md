# Handwritten Digit Classification using CNN

## Overview
This project focuses on classifying handwritten digits from the well-known **MNIST dataset** using a Convolutional Neural Network (CNN). The CNN model utilizes **Max Pooling** layers to effectively reduce dimensionality and enhance feature extraction, leading to high accuracy in digit recognition.

## Introduction
The MNIST dataset is a standard benchmark dataset in the field of machine learning and computer vision. It consists of grayscale images of handwritten digits (0-9) and is widely used to evaluate image classification algorithms. In this project, a Convolutional Neural Network (CNN) was implemented to classify these handwritten digits with high accuracy.

## Dataset
- **Name**: MNIST
- **Number of Classes**: 10 (Digits 0-9)
- **Training Samples**: 60,000 images
- **Testing Samples**: 10,000 images
- **Image Size**: 28x28 pixels, grayscale

## Model Architecture
The CNN architecture used in this project consists of:
- **Convolutional Layers**: For feature extraction from the input images.
- **Max Pooling Layers**: To downsample feature maps while retaining significant information.
- **Fully Connected Layers**: To perform classification based on extracted features.
- **Activation Functions**: ReLU for non-linearity in hidden layers, and Softmax for the output layer to handle multi-class classification (digits 0-9).

### Key Features:
- **Loss Function**: `sparse_categorical_crossentropy` to handle multi-class classification.
- **Data Normalization**: Input pixel values are normalized to a range of [0, 1].
- **Optimizer**: Adam Optimizer for efficient training.

## Results
The model achieved outstanding performance on the MNIST dataset:
- **Training Accuracy**: Over 99%
- **Validation Accuracy**: 98%+
- **Loss**: Reduced significantly over training epochs.
