# Spine-Abnormality-Detection-ML
A deep learning-based medical image analysis system that detects and classifies spinal lumbar stenosis using Convolutional Neural Networks (CNNs). The project incorporates image preprocessing, feature extraction, model training, performance evaluation, and Django-based deployment for automated stenosis stage prediction.



## Overview
Spinal Vision is a deep learning-based healthcare project for automatic detection and classification of spinal lumbar stenosis from medical images. The system is designed to analyze spinal imaging data and classify stenosis severity using Convolutional Neural Network (CNN) architectures.

## Problem Statement
Manual diagnosis of spinal stenosis from medical images can be time-consuming and subjective. This project aims to build an automated system that improves accuracy, consistency, and efficiency in stenosis detection.

## Objectives
- Preprocess spine image datasets for model training
- Train CNN and ANN-based models for classification
- Compare multiple architectures to improve accuracy
- Visualize results using plots and graphs
- Deploy the trained model using a web framework

## Project Scope
The project focuses on the classification of spinal stenosis stages from medical imaging data such as MRI and CT scans. It supports automated feature extraction, image-based prediction, and clinical decision support.

## Key Features
- Image preprocessing using resizing, rescaling, horizontal flip, shear range, and zoom range
- CNN-based feature extraction and classification
- Comparison of more than one architecture for performance improvement
- Visualization of training and evaluation results
- Web deployment for user-friendly prediction

## Classes / Labels
- Normal
- Mild
- Moderate
- Severe

## Technology Stack
- Python
- TensorFlow
- Keras
- CNN
- ANN
- NumPy
- Pandas
- Matplotlib
- Django
- HTML
- CSS
- Bootstrap

## Tools Used
- Anaconda Navigator
- Jupyter Notebook
- PyCharm
- VS Code
- MySQL / SQLite

## Methodology
1. Collect and organize the dataset
2. Preprocess the images
3. Split data into training and testing sets
4. Train CNN/ANN models
5. Compare model performance
6. Evaluate accuracy and other metrics
7. Deploy the trained model in a web application

## Model Architecture
The system uses convolution, pooling, flattening, dense, and softmax layers to learn visual patterns from spine images and classify the stenosis stage.

## Deployment
The trained model is converted into an `.h5` file and deployed using Django with a simple frontend built using HTML, CSS, and Bootstrap.

## Results
The model is evaluated using accuracy and performance metrics. The project aims to provide reliable stenosis classification with improved prediction quality.

## Future Work
- Add more datasets for better generalization
- Improve interpretability of predictions
- Integrate advanced architectures such as ResNet and AlexNet more deeply
- Extend the system for broader spine disorder classification
