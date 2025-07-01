# Object Classification for Automated CCTV

This project focuses on developing an object classification model using computer vision and deep learning techniques. It aims to enhance automated CCTV surveillance systems by detecting and classifying various objects in real-time video feeds.

## 🚀 Project Overview

With the growing need for intelligent surveillance, this project implements an image classification pipeline capable of recognizing different objects commonly captured in CCTV footage. The goal is to integrate object classification into security systems to identify potential threats or anomalies efficiently.

## 🧠 Technologies Used

Python 🐍

TensorFlow & Keras

NumPy

Matplotlib & Seaborn

OpenCV (optional for real-time deployment)

Jupyter Notebook

## 📁 Dataset
The model is trained on the CIFAR-10 dataset, which includes 10 different object categories:

Airplane

Automobile

Bird

Cat

Deer

Dog

Frog

Horse

Ship

Truck

You can download the dataset using:


from tensorflow.keras.datasets import cifar10

## 🧪 Features

Load and preprocess CIFAR-10 dataset

Build a CNN using TensorFlow/Keras

Train and evaluate the model

Visualize predictions using saliency maps and Class Activation Maps (CAM)

Display sample predictions with actual and predicted labels

## 📊 Model Performance
Optimizer: Adam

Loss: Categorical Crossentropy

Evaluation Metrics: Accuracy, Loss

Performance metrics and accuracy scores are shown in the notebook.

## 📸 Visualization

Includes visualization of:

Training and validation accuracy/loss curves

Class Activation Maps (CAM) for model interpretability

Sample predictions with actual labels

## ✅ How to Run

### Clone the repository:

git clone https://github.com/<your-username>/<your-repo-name>.git

cd <your-repo-name>

### Install dependencies:


pip install -r requirements.txt

Run the Jupyter notebook:


jupyter notebook Object-Classification-for-Automated-CCTV.ipynb

## 📌 Requirements

Python 3.7+

Jupyter Notebook

TensorFlow >= 2.0

Matplotlib

Seaborn

NumPy

You can install them with:


pip install tensorflow matplotlib seaborn numpy

## 🤖 Future Scope

Integration with real-time CCTV feed using OpenCV

Object detection using YOLOv5 or Faster R-CNN

Alert system for detecting suspicious activities

