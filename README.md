# 🌍 Landslide Detection using Deep Learning

This project uses deep learning techniques to detect and classify landslide-prone regions from satellite imagery. By leveraging CNN-based architectures, this tool aims to assist disaster management systems and researchers in early identification and risk assessment.

---

## 🚀 Project Overview

Landslides are among the most devastating natural disasters, often leading to significant damage to life and infrastructure. Early detection through satellite imagery can enable proactive disaster management and mitigation strategies.

In this project, we use a Convolutional Neural Network (CNN) to analyze remote sensing data and predict whether a region is likely to experience a landslide.

---

## 📌 Features

- Image classification using deep learning (CNN)
- Landslide vs. Non-landslide region prediction
- Visualization of training metrics (accuracy/loss)
- Model saved and ready for inference
- Scalable for integration with real-time monitoring systems

---

## 🗂️ Dataset

The dataset includes satellite images from multiple regions affected by landslides, sourced from publicly available GIS datasets and disaster archives. It contains:

- `landslide/`: Images labeled as landslide-prone
- `nonlandslide/`: Images labeled as safe or not affected

Each image is resized to 128x128 pixels for consistent input into the CNN model.

---

## 🧠 Model Architecture

We use a sequential CNN with the following layers:

- 2D Convolutional layers with ReLU activation
- MaxPooling layers for spatial reduction
- Dropout layers for regularization
- Dense layers with softmax for binary classification

The model is trained using categorical cross-entropy and Adam optimizer.

---

## 🛠️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/nlskarthikeya27/Landslide-Detection-DL.git
   cd Landslide-Detection-DL/Model
