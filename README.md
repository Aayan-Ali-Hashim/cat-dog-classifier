# 🐶🐱 Cat vs Dog Classifier — CNN + Gradio Demo

This project uses a Convolutional Neural Network (CNN) to classify images as either **cats** or **dogs**.  
The model was trained using TensorFlow/Keras and deployed using Gradio on Hugging Face Spaces.

## 🔗 Live Demo
👉 Try the model here: [Link](https://huggingface.co/spaces/aayan-ali/cat-dog-classifier)

---

## 📓 What's in the Notebook?

The `Cat_vs_Dog.ipynb` notebook contains the full training pipeline:
- Loads the **Dogs vs Cats dataset** from Kaggle
- Preprocesses images using `image_dataset_from_directory`
- Builds a CNN with Conv2D, MaxPooling, BatchNormalization, and Dropout
- Trains the model over 10 epochs and visualizes performance
- Saves the trained model to `.h5` format

You can run the notebook in Colab or locally to see the full process.

---

## 🛠 Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Matplotlib
- Gradio (for app UI)
- Hugging Face Spaces (for deployment)

---

## 🚀 How to Reuse or Extend
- Clone the repo and open the notebook
- Train with your own image data or fine-tune the model
- Deploy your own version with Gradio in Hugging Face Spaces

---

## 🙋‍♂️ Author
**Aayan Ali**  
📧 aayanali1065@gmail.com
💼 [LinkedIn](https://www.linkedin.com/in/aayan-ali-922a14p1b/) | [GitHub](https://github.com/Aayan-Ali-Hashim)

---

## ⭐️ Show Your Support
If you found this project helpful or interesting, feel free to star ⭐ the repo or share the live demo!
