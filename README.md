# Facial Emotion Recognition using CNN

This repository contains the implementation of a Convolutional Neural Network (CNN) for facial emotion recognition. The model leverages deep learning techniques to identify and classify different human emotions from facial images.

## Dataset
The model is trained on the fer2013_csv.csv dataset, which includes pixel-level representations of facial expressions labeled across seven categories: Angry, Disgust, Fear, Happy, Sad, Surprise, and Neutral.


## Model Architecture
The model uses a Residual Network (ResNet) architecture with several Residual Blocks, including convolutional layers with ReLU activation and batch normalization. The network architecture involves initial convolutional layers followed by multiple Residual Blocks, average pooling, and a final dense layer with softmax activation for classification.
<img src="/CNNsModel.png">
