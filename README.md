# Neural Network for Breast_Cancer Classification using PyTorch
This repository contains a Jupyter Notebook that implements a Neural Network for Breast Cancer Classification using Python and machine learning libraries. The model is trained on the Breast Cancer Wisconsin (Diagnostic) dataset to classify tumors as benign or malignant.

# Dataset
The notebook uses the Breast Cancer Wisconsin (Diagnostic) dataset, which is available in the sklearn.datasets module. It includes 30 features computed from digitized images of fine needle aspirate (FNA) of breast masses.

# Target Variable:
Malignant (1)
Benign (0)

# Model Architecture
The neural network is built using PyTorch and consists of the following layers:
Input Layer: Accepts 30 features
Hidden Layers: Fully connected layers with activation functions
Output Layer: Sigmoid activation for binary classification

# Training and Evaluation
The dataset is split into training and testing sets.
The model is compiled using binary cross-entropy loss and Adam optimizer.
Performance is evaluated using accuracy, confusion matrix, and classification report.

# Results
The trained model achieves high accuracy in classifying breast cancer tumors, demonstrating the effectiveness of neural networks in medical diagnostics.
