# Handwritten Character Recognition ✏️🤖

This repository features a production-style Deep Learning pipeline utilizing a 2D Convolutional Neural Network (CNN) to automatically recognize and classify handwritten characters. Developed during the CodeAlpha Machine Learning Internship.

## 🎯 Objective
To engineer a spatial deep learning model capable of processing grayscale image data, extracting complex feature hierarchies (edges, shapes, loops), and accurately classifying handwritten data with minimal error rates.

## 🛠️ Architecture & Tech Stack
* **Framework:** TensorFlow / Keras
* **Libraries:** NumPy, Matplotlib, Scikit-learn
* **Model Topology:** * `Conv2D` layers for spatial feature mapping.
  * `MaxPooling2D` for downsampling and translational invariance.
  * `Dropout` layers (0.25 & 0.5) to enforce regularization and eliminate overfitting.
  * Fully Connected `Dense` layer with a `Softmax` activation function for multi-class classification.

## 📈 Dataset
The model leverages the **MNIST digits dataset** (pre-loaded via TensorFlow), consisting of 60,000 training images and 10,000 testing images of 28x28 grayscale handwritten digits. The input tensors are normalized to a `[0, 1]` range prior to training.

## 🚀 Execution Guide
1. Launch the `Handwritten_Character_Recognition.ipynb` notebook within Google Colab.
2. Select a GPU hardware accelerator (e.g., T4 GPU) via the runtime options for optimal performance.
3. Run the cell to fetch data, execute preprocessing pipelines, train the CNN architecture, and render live visual predictions.

---
*Developed by Muhammad Zeeshan | AI/ML Engineer*
