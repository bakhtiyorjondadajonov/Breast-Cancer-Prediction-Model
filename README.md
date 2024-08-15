# Breast-Cancer-Prediction-Model

## Project Description
This project provides a machine learning solution for predicting breast cancer using a neural network built with TensorFlow. The model predicts whether a breast cancer tumor is malignant or benign based on features extracted from digitized images of fine needle aspirates (FNAs) of breast masses. The dataset used is the **Breast Cancer Wisconsin Dataset**, a well-known dataset available in Scikit-learn.
## Key Features
- **Data Handling and Preprocessing**: The dataset is standardized using Scikit-learn's `StandardScaler` to ensure uniform feature contributions during model training.
- **Model Architecture**: A neural network is constructed using TensorFlow, designed to perform binary classification.
- **Training and Evaluation**: The model is trained on a subset of the dataset and evaluated on a separate test set to measure its performance.

## TensorFlow Implementation
TensorFlow is used to build, train, and evaluate the neural network, with features such as Dense layers, activation functions (e.g., ReLU, Sigmoid), and optimizers (e.g., Adam) being utilized.

![accuracy](https://github.com/user-attachments/assets/d1b771cf-44b1-4939-9de2-42f665a7a51a)
![loss](https://github.com/user-attachments/assets/2525c310-b210-44c8-af0f-84780b955430)

## Installation
To run this project locally, ensure you have the following dependencies installed:
- Python 3.x
- TensorFlow
- Scikit-learn

