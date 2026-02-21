# 🍎 Fruitify - Intelligent Fruit Classification System

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)
![Keras](https://img.shields.io/badge/Keras-2.x-red)
![License](https://img.shields.io/badge/License-MIT-green)

## 📋 Overview

**Fruitify** is a deep learning-based image classification system developed for COM 3303 - Artificial Intelligence mini project. The system uses Convolutional Neural Networks (CNNs) to automatically identify and classify different types of fruits from digital images.

## 🎯 Project Objectives

- ✅ Design and implement a CNN-based fruit classification model
- ✅ Preprocess and augment fruit image dataset
- ✅ Achieve minimum 85% classification accuracy
- ✅ Compare baseline vs improved model performance
- ✅ Demonstrate practical AI application in food recognition

## 🗂️ Dataset

- **Source:** [Fruit-360 Dataset](https://www.kaggle.com/datasets/moltean/fruits) from Kaggle
- **Classes:** 10 fruit categories
  - Apple, Banana, Orange, Strawberry, Grape
  - Mango, Pineapple, Watermelon, Peach, Pear
- **Images:** ~5,000 total (500 images per class)
- **Split:** 64% Training | 16% Validation | 20% Testing

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/Fruitify-Image-Classifier.git
   cd Fruitify-Image-Classifier
   ```
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🚀 Usage

1. Place your fruit images in the `data/` directory.
2. Open the Jupyter Notebook `Fruitify_Image_Classifier (1).ipynb` in the `Implementation_1/` folder.
3. Follow the steps in the notebook to preprocess the data, train the model, and evaluate its performance.
4. To test the model on new images, use the `predict()` function provided in the notebook.

## 🧠 Model Architecture

The Fruitify model is built using TensorFlow and Keras. It employs a Convolutional Neural Network (CNN) architecture with the following layers:

- Convolutional layers with ReLU activation
- MaxPooling layers for down-sampling
- Fully connected dense layers
- Softmax activation for multi-class classification

## 📊 Results

- **Training Accuracy:** 92%
- **Validation Accuracy:** 88%
- **Testing Accuracy:** 87%

The model successfully achieved the target accuracy of 85% and demonstrated robust performance on unseen data.

