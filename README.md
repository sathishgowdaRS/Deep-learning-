# Deep Learning – MNIST Handwritten Digit Classification

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/10EdxMXJghEK6X5KbdpVSqIdgwdkyP8ZE?usp=sharing)

## Project Description

This project focuses on handwritten digit classification using Deep Learning and the MNIST handwritten digit dataset.

A simple neural network is developed using TensorFlow/Keras to classify handwritten digits from 0 to 9. The project includes dataset exploration, preprocessing, model training, evaluation, visualization, prediction, and a simple model experiment.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Features

- Load and explore the MNIST dataset
- Display sample handwritten digit images
- Normalize image pixel values
- Design, compile, and train a neural network
- Evaluate the model using test accuracy
- Visualize training and validation accuracy
- Visualize training and validation loss
- Test the model on 5 handwritten digit images
- Compare actual and predicted labels
- Change the number of neurons and compare model results

## Neural Network Architecture

- **Flatten layer:** Converts each 28 × 28 image into 784 values
- **Dense layer:** 128 neurons with ReLU activation
- **Output layer:** 10 neurons with Softmax activation

The model uses the Adam optimizer and Sparse Categorical Cross-Entropy loss and is trained for 5 epochs.

## Dataset

The project uses the MNIST handwritten digit dataset through TensorFlow/Keras.

- 60,000 training images
- 10,000 testing images
- Image size: 28 × 28 pixels
- 10 classes: digits 0–9
- Grayscale images

## Applications

- Handwritten digit recognition
- Optical Character Recognition (OCR)
- Document digitization
- Number recognition
- Postal code recognition

## Output

The project produces:

- Sample MNIST handwritten digit images
- Training and validation accuracy graph
- Training and validation loss graph
- Test accuracy
- Actual vs predicted labels for 5 images
- Comparison between the original and modified neural network

## Experiment

The hidden layer is changed from **128 neurons to 64 neurons**. Both models are trained using the same dataset and settings, and their test accuracy is compared.

## Google Colab

[Open the Assignment in Google Colab](https://colab.research.google.com/drive/10EdxMXJghEK6X5KbdpVSqIdgwdkyP8ZE?usp=sharing)
