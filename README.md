# Cat and Dog Image Classification

## Overview
This project aims to classify images of cats and dogs using a convolutional neural network (CNN). The model is trained on a dataset of labeled cat and dog images and can accurately distinguish between the two classes.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Results](#results)

## Introduction
This project demonstrates the use of deep learning for image classification. We use a CNN to classify images of cats and dogs. The model is built using TensorFlow and Keras.

## Dataset
The dataset used for this project is the [Kaggle Dogs vs. Cats dataset](https://www.kaggle.com/datasets/salader/dogs-vs-cats). It contains 25,000 images of cats and dogs, split into training and validation sets.

## Model Architecture
The model is a convolutional neural network (CNN) with the following architecture:
-Libraries: Keras and TensorFlow
- Input layer
- Convolutional layers with ReLU activation
- Max-pooling layers
- Fully connected (dense) layers
- Output layer with softmax activation

## Training
The model is trained using the Google Colab GPU. Data augmentation is applied to increase the diversity of the training data.

## Evaluation
The model's performance is evaluated using accuracy, precision, recall, and F1-score. The evaluation metrics are calculated on the validation set.

## Results
The model achieves an accuracy of approximately 90% on the validation set. Detailed results and performance metrics are provided in the results directory.
