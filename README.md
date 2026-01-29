# Potato Disease Classification using Deep Learning

This project implements a Convolutional Neural Network (CNN) to classify potato leaf diseases into three categories: **Early Blight**, **Late Blight**, and **Healthy**. The model is built using TensorFlow and Keras to assist in automated agricultural diagnostics.

## 🚀 Project Overview
Potato crops are highly susceptible to blight diseases which can significantly impact yield. This repository provides an end-to-end machine learning pipeline—from data preprocessing to model evaluation—to accurately identify these conditions from leaf images.

## 📊 Dataset
The model is trained on the **PlantVillage dataset**, which includes:
- **Total Images:** 2,152 files
- **Classes:** 3 (`Potato___Early_blight`, `Potato___Late_blight`, `Potato___healthy`)
- **Image Size:** 256x256 pixels

## 🛠️ Technical Stack
- **Framework:** TensorFlow / Keras
- **Data Handling:** NumPy, TensorFlow Dataset API
- **Visualization:** Matplotlib
- **Training Environment:** Jupyter Notebook (.ipynb)

## 🏗️ Model Architecture
The project utilizes a Sequential Neural Network with the following key components:
- **Data Augmentation:** Rescaling and preprocessing layers to improve model robustness.
- **Hidden Layers:** Dense layers utilizing **ReLU** activation functions for feature extraction.
- **Output Layer:** A Dense layer with **Sigmoid/Softmax** activation for 3-class classification.
- **Optimizer:** Adam Optimizer.
- **Loss Function:** Sparse Categorical Crossentropy.

## 📈 Performance
The model achieves high accuracy by evolving from a simple linear structure to a deep neural network with hidden layers.
- **Final Accuracy:** ~97.7% on the test dataset.
