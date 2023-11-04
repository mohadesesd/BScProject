# Multi-Input Model for RNA Sequence Interaction Prediction

## Introduction

This repository contains a multi-input neural network model that predicts if two RNA sequences have interaction.

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
