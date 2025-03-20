# Autoencoder for Image Denoising

This project implements a convolutional autoencoder using Keras and TensorFlow for image denoising on the MNIST dataset.

## Introduction
This project trains a convolutional autoencoder to remove noise from images. The model learns to encode noisy images and reconstruct denoised versions.

## Features
- Uses **Convolutional Neural Networks (CNNs)** for encoding and decoding.
- **Denoising autoencoder**: Removes noise from input images.
- **Trained on the MNIST dataset**, a widely used dataset of handwritten digits.
- **Noisy dataset generation**: Adds Gaussian noise to MNIST images.
- **Visualization**: Compares original noisy images with denoised outputs.
  
## Dataset
The MNIST dataset is used, consisting of grayscale handwritten digits (0-9) of size 28x28 pixels.

## Training
The model is trained using the following steps:

1. Load the MNIST dataset.
2. Normalize and reshape images.
3. Add Gaussian noise to the dataset.
4. Train the autoencoder using binary cross-entropy loss and the Adam optimizer.
5. Validate performance using test images.


## Results
The model effectively removes noise from images. Below is a comparison of noisy and denoised images:
![image](https://github.com/user-attachments/assets/3b608013-9a22-4992-a252-1cb3fda4449b)


## Libraries Used
- `numpy` - For numerical operations.
- `matplotlib` - For visualization.
- `keras` - For building the neural network.
- `tensorflow` - Backend for deep learning.

