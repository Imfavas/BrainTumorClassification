# Brain Tumor Classification Using CNN

This repository contains a Convolutional Neural Network (CNN) project designed to classify brain tumors into four categories: glioma, meningioma, notumor, and pituitary. The project showcases skills in deep learning, image processing, and file management for medical image classification.

## Project Overview

- **Objective**: Classify brain tumor images into four distinct categories.
- **Approach**:
  - **Data Pipeline**: Load and preprocess images from a folder into a `.npz` file.
  - **Efficient File Handling**: Use a custom script to move processed files into a separate directory to avoid redundant loading.
  - **Model Development**: Build and train a CNN model using TensorFlow, with data handling and preprocessing facilitated by libraries such as NumPy, OpenCV (cv2), shutil, os, and scikit-learn.
  - **Model Saving & Evaluation**: Save the best-performing model as `best_model.keras` and evaluate its performance metrics.

## Features

- **Efficient Data Processing**: Converts raw images into a compressed `.npz` file for faster loading and processing.
- **Image Preprocessing**: Utilizes OpenCV for reading and preprocessing images.
- **CNN Model**: Developed using TensorFlow to perform multi-class classification.
- **Custom File Management**: Automatically relocates processed files to prevent redundant processing.
- **Performance Metrics**: Comprehensive evaluation of model performance with metrics computed using scikit-learn.

## Requirements

- Python 3.x
- TensorFlow
- NumPy
- OpenCV (cv2)
- scikit-learn
- Additional standard libraries: shutil, os

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Imfavas/BrainTumorClassification.git
   cd brain-tumor-classification
```
