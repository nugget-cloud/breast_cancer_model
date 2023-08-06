Breast Ultrasound Image Classification
Overview

This project aims to classify breast ultrasound images into normal, benign, and malignant. It uses a Convolutional Neural Network (CNN) to train on a dataset containing breast ultrasound images and their corresponding labels.
Dataset

The dataset consists of ultrasound images of female patients aged between 25 and 75. The photos are categorized into three classes:

    Normal
    Benign
    Malignant

Each class has both the original ultrasound image and its corresponding mask.
Dependencies

    Python 3.x
    PyTorch
    torchvision
    PIL (Pillow)
    NumPy
    scikit-learn

Model Architecture

The model architecture is a simple CNN with three convolutional layers and two fully connected layers. The model uses ReLU activations and max-pooling. There's also a dropout layer to prevent overfitting.
Results

The trained model achieved a validation accuracy of 54%. Further improvements are planned, including data augmentation, regularization, and potentially leveraging transfer learning.
Contributing

Just to let you know, pull requests are welcome. For significant changes, please open an issue first to discuss what you'd like to change.

