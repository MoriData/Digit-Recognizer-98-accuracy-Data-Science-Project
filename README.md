# Digit Recognizer - 98% Accuracy

This project explores digit recognition using a Convolutional Neural Network (CNN) to achieve a **98% accuracy** rate. It is part of the **Digit Recognizer** competition on Kaggle, which uses the popular MNIST dataset.

## Overview
The objective of this project is to build a machine learning model capable of accurately recognizing handwritten digits (0-9). By training on thousands of images of digits, this model learns to distinguish subtle features for high-accuracy predictions.

## Dataset
The MNIST dataset includes:
- **Training set**: 42,000 images, 28x28 pixels each, labeled from 0 to 9.
- **Test set**: 28,000 images with the same format for model evaluation.

Each image represents a single handwritten digit. Data preprocessing steps are included to normalize pixel values and reshape the data.

## Model and Methodology
- **Model Architecture**: The model is a CNN with several convolutional and pooling layers, followed by dense layers to classify the digits. This setup ensures the model captures essential spatial patterns in the images.
- **Optimizer**: Adam optimizer is used to train the model efficiently.
- **Loss Function**: Categorical Crossentropy
- **Metrics**: Accuracy

## Key Steps
1. **Preprocessing**: Pixel values are scaled, and the images are reshaped.
2. **Model Training**: The CNN is trained using a validation set for tuning.
3. **Evaluation**: The model is evaluated on the test set, achieving 98% accuracy.

## Results
Achieving 98% accuracy, this model is effective at digit recognition and could be improved further with hyperparameter tuning or additional training epochs.
