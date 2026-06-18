# Image-Classification-with-Tensorflow

## Overview

This project implements a handwritten digit classification model using TensorFlow and the MNIST dataset. The model is trained to recognize digits from 0–9 based on grayscale images of handwritten numbers.

The project demonstrates the complete machine learning workflow, including data preprocessing, label encoding, neural network construction, model training, evaluation, and prediction visualization.

## Dataset

The model uses the MNIST dataset, which contains:

* 60,000 training images
* 10,000 testing images
* 28 × 28 grayscale images of handwritten digits
* 10 output classes (digits 0–9)

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Jupyter Notebook / Google Colab

## Project Workflow

### 1. Data Loading

* Imported the MNIST dataset using TensorFlow.
* Explored image dimensions and class labels.

### 2. Data Preprocessing

* Reshaped images from 28 × 28 matrices into 784-dimensional vectors.
* Applied normalization to improve model performance.
* Performed one-hot encoding on labels.

### 3. Model Development

Built a feedforward neural network using Keras Sequential API:

* Dense Layer (128 neurons, ReLU)
* Dense Layer (128 neurons, ReLU)
* Output Layer (10 neurons, Softmax)

### 4. Model Training

* Optimizer: Stochastic Gradient Descent (SGD)
* Loss Function: Categorical Crossentropy
* Training Epochs: 3

### 5. Evaluation

The trained model achieved approximately **95.76% test accuracy** on the MNIST dataset.

### 6. Prediction Visualization

* Generated predictions on unseen test images.
* Visualized predicted and actual labels.
* Highlighted correct and incorrect classifications.

## Key Concepts Learned

* Image Classification
* Neural Networks
* TensorFlow & Keras
* Data Normalization
* One-Hot Encoding
* Activation Functions (ReLU & Softmax)
* Model Training and Evaluation
* Prediction Analysis

## Future Improvements

* Experiment with Convolutional Neural Networks (CNNs)
* Increase training epochs
* Add data augmentation
* Compare different optimizers and architectures

## What I Learned

This project introduced me to the fundamentals of deep learning and image classification. I gained hands-on experience working with TensorFlow, preparing image data for machine learning models, training neural networks, evaluating performance, and interpreting prediction results.
