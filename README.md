# MNIST Handwritten Digit Recognition
Image from dataset
<br>
![MNIST_Dataset](MNIST-handwritten-digits-dataset-visualized.png)
<br>
<br>
A deep learning project implementing a Convolutional Neural Network (CNN) to recognize handwritten digits from the MNIST dataset. The model achieves an accuracy of **99.23%** on the test set, demonstrating a highly effective approach to image classification.

## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project focuses on building a CNN model to accurately classify handwritten digits (0-9) using the MNIST dataset. The model is trained, validated, and evaluated with robust metrics and visualizations to ensure high performance. This project serves as a foundational approach to image recognition and computer vision tasks.

## Dataset

The MNIST dataset consists of 60,000 training images and 10,000 test images of handwritten digits, each of size 28x28 pixels in grayscale. The dataset is a standard benchmark for image classification and provides a great starting point for learning CNN architectures.

- **Training Set:** 60,000 images
- **Test Set:** 10,000 images
- **Classes:** 10 (digits 0-9)

## Model Architecture

The Convolutional Neural Network (CNN) used in this project comprises:

- **Convolutional Layers**: Extract features using multiple filters.
- **Pooling Layers**: Reduce the dimensionality of feature maps.
- **Fully Connected Layers**: Combine features to predict the digit class.
- **Activation Functions**: Relu for non-linearity and Softmax for classification.

## Training

- **Loss Function:** Categorical Crossentropy
- **Optimizer:** Adam
- **Epochs:** 50
- **Batch Size:** 128
  

## Results

The model achieved an impressive accuracy of **99.23%** on the test set. 

### Key Metrics

- **Test Accuracy:** 99.23%
- **Training vs Validation Loss:** Both loss curves show a stable convergence, indicating effective model training without significant overfitting.

## Installation

To run the project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/CodeNinajaSarthak/MNIST-Handwritten-Digit-Recognition.git
   cd MNIST-Handwritten-Digit-Recognition
