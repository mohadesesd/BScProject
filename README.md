# BScProject

# Multi-Input Model for RNA Sequence Feature Learning

## Introduction

This repository contains a multi-input neural network model that learns features from RNA transcript sequences. The model processes two separate RNA sequence inputs, extracts features through convolutional layers, and then combines them to predict associated labels through fully connected layers.

## Model Architecture

The model uses two input sequences, which go through separate embedding and convolutional layers. These layers are designed to capture the features of the RNA sequences effectively. After a series of convolutional and max-pooling operations, the feature maps are flattened and combined. The merged feature vector is then passed through fully connected layers to make the final prediction.

## Dependencies

- Python 3.x
- TensorFlow 2.x
- Keras

Use the following command to install the required libraries:

```bash
pip install tensorflow
pip install keras
```
