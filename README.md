# Music-Genre-Recognition


---


## 💡 Overview

This repository details a Deep Learning project focused on Music Genre Recognition using Feedforward Neural Networks (FNNs) and Convolutional Neural Networks (CNNs).
The project demonstrates key skills in handling audio data features (Mel-Spectrograms), building modern deep learning architectures, utilizing GPU acceleration, and performing comprehensive model evaluation.


---


## ⚙️ Features

- **Load Dataset**: Transform the labels on the dataset from strings to integers but keeping the correlation between the integers and the strings.
- **FNN Implementation**: A simple FNN model is implemented as a baseline.
- **CNN Implementation**: A more advanced CNN model is developed, featuring: Multiple Convolutional Layers, Max Pooling for feature reduction, Batch Normalization, Dropout for regularization and SGD Optimizer with momentum and Cross-Entropy Loss.
- **Training and Optimization**: Use of a fixed random seed to ensure reproducible results. Then implemented a training loop where it iterates through epochs, it has forward and backward passes, updates parameters and monitors loss and accuracy.
- **Evaluation**: Model performance is primarily evaluated using Test Accuracy and F1-Score and visualize of the Confusion Matrix to analyze per-genre performance and identify common misclassifications.
- **Interface**: You can provide a link from a youtube video to use the final trained CNN model to predict the genre for each second of the clip.


---


## 🧰 Technologies Used & Libraries
- **Language**: Python 3
- **Framework**: Jupyter Notebook
- **Matrix Handling/ Numerical Operations**: numpy, pandas
- **PyTorch (Deep Learning, GPU)**: torch
- **Model Evaluation**: scikit-learn
- **Visualization**: matplotlib, seaborn
