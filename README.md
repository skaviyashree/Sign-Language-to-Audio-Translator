# 🤟 Sign Language to Audio Translator

A real-time Sign Language Recognition system that uses a **Convolutional Neural Network (CNN)** to recognize hand gestures through a webcam and converts the recognized sign into corresponding audio output.

The project is trained using the **Sign Language MNIST dataset**, where hand gesture images are processed and classified using a CNN model. The trained model is then used for real-time gesture recognition through a webcam.

---

## 📌 Project Overview

Communication can be challenging for people who use sign language when interacting with people who do not understand it.

This project aims to reduce this communication gap by developing a system that:

1. Captures a hand gesture using a webcam.
2. Processes the captured image.
3. Uses a trained CNN model to recognize the sign.
4. Stabilizes predictions using a prediction history buffer.
5. Converts the recognized sign into an audio output.

---

## 🎯 Project Objective

The main objective of this project is to develop a real-time system capable of recognizing static sign language gestures and providing the corresponding audio output.

---

## ⚙️ Technologies Used

- Python
- NumPy
- Pandas
- TensorFlow / Keras
- OpenCV
- Scikit-learn
- Windows `winsound` library

---

## 📂 Project Workflow

The project consists of three major stages:

```text
Sign Language MNIST Dataset
            │
            ▼
     Data Preprocessing
            │
            ▼
       CNN Training
            │
            ▼
      Trained CNN Model
            │
            ▼
    Real-Time Webcam Input
            │
            ▼
      Image Preprocessing
            │
            ▼
       Gesture Prediction
            │
            ▼
    Prediction Stabilization
            │
            ▼
        Audio Output
