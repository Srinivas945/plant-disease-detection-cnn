# 🌱 Plant Disease Detection Using CNN

## 📌 Project Overview

This project uses a Convolutional Neural Network (CNN) to classify plant
leaf images into different disease categories using the PlantVillage dataset.

The model is trained using TensorFlow and Keras and runs on a Google Colab
NVIDIA T4 GPU.

## 🎯 Objectives

- Analyze the PlantVillage image dataset
- Preprocess plant leaf images
- Apply image augmentation
- Build a CNN model from scratch
- Train and validate the CNN
- Evaluate the model using accuracy, precision, recall and F1-score
- Generate a confusion matrix
- Predict the disease class of a new leaf image

## 📊 Dataset

The project uses the PlantVillage dataset.

The dataset contains **15 plant disease classes** and thousands of leaf images.

The dataset is downloaded using KaggleHub during notebook execution.

## 🧠 CNN Architecture

The CNN contains:

- Convolutional layers
- Max Pooling layers
- ReLU activation
- Flatten layer
- Dense layers
- Dropout
- Softmax output layer

### Model Flow

Image → Convolution → Pooling → Convolution → Pooling →  
Convolution → Pooling → Convolution → Pooling →  
Flatten → Dense → Dropout → Classification

## 🔧 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Google Colab
- NVIDIA T4 GPU

## 📈 Model Evaluation

The CNN model is evaluated using:

- Accuracy
- Loss
- Precision
- Recall
- F1-score
- Confusion Matrix

## 🔍 Prediction

The trained CNN can accept a new plant leaf image and predict its
corresponding disease class along with the prediction confidence.

## 📁 Repository Structure

```text
plant-disease-detection-cnn/
│
├── Plant_Disease_Detection_CNN.ipynb
└── README.md
