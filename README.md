# Multiclass Image Classification using CNN

## Overview

This project implements a multiclass image classification model using a Convolutional Neural Network (CNN) with Python, TensorFlow and Keras.

The project uses the Intel Image Classification dataset, which contains images belonging to six categories:

- Buildings
- Forest
- Glacier
- Mountain
- Sea
- Street

The objective is to train a CNN model that can identify the category of an input image.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- PIL

## Project Workflow

1. Load the image dataset
2. Resize the images to 150 × 150 pixels
3. Prepare the image datasets for training and testing
4. Build a Convolutional Neural Network
5. Train the model using the training dataset
6. Evaluate the trained model
7. Make predictions on individual images
8. Save the trained model

## CNN Architecture

The CNN consists of:

- Convolutional layers
- Max Pooling layers
- Flatten layer
- Dense layers
- Dropout layers
- Softmax output layer

The final layer produces predictions for the six image categories.

## Dataset Classes

The model classifies images into the following categories:

| Class | Description |
|---|---|
| Buildings | Images of buildings |
| Forest | Images of forests |
| Glacier | Images of glaciers |
| Mountain | Images of mountains |
| Sea | Images of the sea |
| Street | Images of streets |

## Prediction

After training, the model can be used to predict the class of an individual image. The predicted class index is mapped to its corresponding category.

## Model Saving

The trained CNN model is saved in Keras format for later use.

## Project Files

```text
Intel-Image-Classification/
│
├── Multiclass_image_classification_intel_images.ipynb
└── README.md
