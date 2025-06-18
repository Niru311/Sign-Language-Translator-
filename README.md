# 🧠 Sign Language Translator using CNN and OpenCV

A real-time American Sign Language (ASL) translator using a Convolutional Neural Network (CNN) trained on the [Sign Language MNIST dataset](https://www.kaggle.com/datamunge/sign-language-mnist) and OpenCV for live webcam prediction.

---

## 🚀 Features

- CNN-based image classification model for ASL signs
- Trained on Sign Language MNIST dataset
- Real-time sign recognition using webcam
- Prediction smoothing with a rolling buffer for stability

---

## 🧰 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Scikit-learn
- Sign Language MNIST dataset

---

## 🎯 How It Works
📊 Training the CNN Model
The dataset contains grayscale 28x28 images of hand signs representing A–Z (excluding J). Each row in the CSV contains a label (0–25) followed by pixel values.

Run the following command to train the model:
-python sign_language_translator.py
---

## 🔤 Supported Sign Labels
All uppercase English letters except J:J is excluded due to its dynamic nature, which isn’t captured in static images.
---



