# Image Classification with CNN using TensorFlow and Keras

This repository contains a project on image classification using Convolutional Neural Networks (CNN) with TensorFlow and Keras. The model is trained to classify images from a dataset into different categories.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project demonstrates the use of a Convolutional Neural Network (CNN) for image classification. CNNs are widely used in computer vision tasks due to their ability to automatically learn spatial hierarchies of features from images.

## Dataset

The dataset used in this project is divided into training, validation, and test sets. Each set contains images categorized into different classes.

- Training set: Used to train the model.
- Validation set: Used to validate the model during training.
- Test set: Used to evaluate the final performance of the model.

## Model Architecture

The model architecture consists of the following layers:
- Convolutional layers with ReLU activation and Max Pooling
- Flattening layer to convert 2D matrices into a 1D vector
- Fully connected layer with softmax activation for classification
