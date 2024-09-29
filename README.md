# EEG Signal Classification using Ensemble Learning

This project implements an ensemble learning approach for classifying EEG signals into three categories: Ictal, Interictal, and Normal. It uses a combination of machine learning algorithms and deep learning feature extraction techniques to achieve high accuracy in EEG signal classification.

## Features

- Data loading and preprocessing of EEG signals
- Feature extraction using MobileNet, VGG16, and LeNet architectures
- Ensemble of multiple classifiers including Random Forest, Gradient Boosting, SVM, KNN, and Logistic Regression
- Hyperparameter tuning using custom grid search with timeout
- Cross-validation for robust performance estimation
- Visualization of model performance, learning curves, and confusion matrices

## Requirements

- Python 3.7+
- See `requirements.txt` for required packages

## Usage

1. Ensure your EEG data is organized in the following structure:
