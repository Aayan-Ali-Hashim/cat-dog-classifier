
# 🐶🐱 Cat vs Dog Classifier

A deep learning project using a Convolutional Neural Network (CNN) to classify images as either **cats** or **dogs**, with a clean **Gradio UI** and **deployment on Hugging Face Spaces**.

## 🔗 Try It Live
👉 [Click here to use the classifier](https://huggingface.co/spaces/aayan-ali/cat-dog-classifier)

## 📌 Project Overview
This project demonstrates how to:
- Build an image classifier using **TensorFlow and Keras**
- Preprocess and normalize image datasets
- Train a CNN model to distinguish between cats and dogs
- Deploy the model with an interactive UI using **Gradio**
- Host the app for free using **Hugging Face Spaces**

## 🧠 Model Architecture
- **Input:** RGB images, resized to 256x256
- **3 Convolutional Layers** with ReLU activation + MaxPooling
- **Batch Normalization** & **Dropout** to prevent overfitting
- **Fully connected layers**
- **Sigmoid output** for binary classification (Cat vs Dog)

## 📁 Dataset
- [Dogs vs Cats Dataset from Kaggle](https://www.kaggle.com/datasets/salader/dogs-vs-cats)
- Used `image_dataset_from_directory()` to load and preprocess

## 🚀 How to Run Locally

### 1. Clone the repository
```bash
git clone https://github.com/Aayan-Ali-Hashim/cat-dog-classifier.git
cd cat-dog-classifier
