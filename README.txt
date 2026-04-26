Face Mask Detection using Deep Learning

## Overview

This project builds a Convolutional Neural Network (CNN) model to detect whether a person is wearing a face mask or not using real-world image data.

##  Dataset

* Source: Kaggle Face Mask Detection Dataset
* Contains images with annotations (bounding boxes)
* Classes used:

  * With Mask
  * Without Mask

##  Tech Stack

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib
* Scikit-learn

##  Model Architecture

* Convolutional Layers (32, 64, 128 filters)
* MaxPooling Layers
* Fully Connected Dense Layers
* Dropout (to prevent overfitting)
* Sigmoid output for binary classification

##  Workflow

1. Download dataset using kagglehub
2. Extract faces using XML annotations
3. Preprocess images (resize, normalize)
4. Train CNN model
5. Evaluate performance
6. Visualize results

##  Results

* Achieved high accuracy of over 97% on validation data
* Model successfully distinguishes masked vs unmasked faces
