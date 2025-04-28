# Image_Classifier_CNN_Data_Augmentation

## Project Description
This project focuses on developing and optimizing a multi-class image classification model using Convolutional Neural Networks (CNNs) on the CIFAR-10 dataset. The project incorporates key deep learning techniques, such as data augmentation (random flip, rotation, and crop), batch normalization, and ReLU activation, to enhance the model’s performance. The final model achieved a test accuracy of 76.86%, demonstrating significant improvement over the baseline.

## Techniques and Technologies Used
Model Architecture: Convolutional Neural Networks (CNNs) with fully connected layers.

Key Techniques:

Data Augmentation: Random Horizontal Flip, Rotation, Random Crop with Padding.

Batch Normalization for faster convergence and model stabilization.

ReLU Activation to introduce non-linearity.

Adam Optimizer for efficient training and weight updates.

Cross-Entropy Loss for multi-class classification.

## Data
Dataset: CIFAR-10 dataset, consisting of 60,000 32x32 color images in 10 classes, with 6,000 images per class.

Data Preprocessing:

Image normalization (scaling pixel values to [-1, 1]).

Data augmentation techniques for better generalization.

## Model Evaluation
Test Accuracy: 76.86% after applying data augmentation.

Improvement: Achieved an 11% increase in accuracy compared to the baseline model (65.86%).

Epochs Trained: 20 epochs.

Loss Function: Cross-Entropy Loss.

Optimizer: Adam Optimizer with a learning rate of 0.001.
