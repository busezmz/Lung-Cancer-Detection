# Lung Cancer Classification and Detection

This project focuses on the **automatic detection and classification of lung cancer** using **Convolutional Neural Networks (CNNs)** on **histopathological images**. The goal is to classify lung tissue images into three categories:

- **ACA**: Adenocarcinoma (cancerous)
- **SCC**: Squamous Cell Carcinoma (cancerous)
- **N**: Normal (healthy)

Manual classification of medical images is time-consuming and highly expertise-dependent. This project offers an automatic, accurate, and fast solution to aid early diagnosis and treatment planning.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation and Usage](#installation-and-usage)
- [Results](#results)
- [Future Work](#future-work)
- [Acknowledgements](#acknowledgements)

---

## Project Overview

The project develops a CNN-based deep learning model for the classification of lung cancer tissue images.  
A total of **15,000 histopathological images** are used to train and test the model.

Key points:
- Improves diagnosis speed and accuracy.
- Reduces human error in medical image analysis.
- Uses deep learning models like **EfficientNetB3**, **VGG16**, **ResNet**, and **GoogleNet** concepts.

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- EfficientNet

---

## Dataset

The dataset consists of histopathological images labeled as:
- **Adenocarcinoma (ACA)**
- **Squamous Cell Carcinoma (SCC)**
- **Normal (N)**

Dataset Source: [Kaggle - Lung and Colon Cancer Histopathological Images](https://www.kaggle.com/andrewmvd/lung-and-colon-cancer-histopathological-images)

---

## Model Architecture

The model includes the following layers:

- **Conv2D** (Convolution)
- **MaxPooling2D** (Pooling)
- **Dropout** (Regularization)
- **BatchNormalization** (Normalization)
- **Flatten** (Reshaping)
- **Dense** (Fully connected layers)

Additional concepts:
- **Padding** to maintain spatial dimensions
- **Strided Convolutions** for efficient downsampling
- **Data augmentation** and **early stopping** strategies for better generalization


Install the required packages:
pip install tensorflow keras numpy pandas matplotlib seaborn scikit-learn

Open the notebook:
jupyter notebook BuseAzmaz_190441046_SeniorProject-2.ipynb
