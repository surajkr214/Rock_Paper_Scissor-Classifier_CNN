# Rock_Paper_Scissor-Classifier_CNN
End-to-end Deep Learning pipeline using a custom CNN architecture to classify hand gestures (Rock, Paper, Scissors) with high accuracy. Deployed as a scalable microservice using FastAPI and Docker.

# Rock_Paper_Scissor-Classifier_CNN 🖐️✊✌️

![Python](https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange?style=for-the-badge&logo=tensorflow)
![FastAPI](https://img.shields.io/badge/FastAPI-0.68-green?style=for-the-badge&logo=fastapi)
![Docker](https://img.shields.io/badge/Docker-Container-blue?style=for-the-badge&logo=docker)

## 📌 Project Overview
This project implements a robust **Convolutional Neural Network (CNN)** for multi-class image classification, specifically designed to recognize hand gestures for Rock, Paper, and Scissors.

Going beyond simple model training, this repository demonstrates a complete **MLOps workflow**:
1.  **Model Training:** A custom CNN architecture trained on image data using TensorFlow/Keras.
2.  **Inference API:** A high-performance REST API built with **FastAPI** to serve predictions in real-time.
3.  **Containerization:** Fully dockerized application ensuring consistency across development and production environments.
4.  **Deployment:** Cloud-ready architecture (deployed on Render).

## 🚀 Key Features
* **Deep Learning Core:** Utilizes Conv2D, MaxPooling, and Dropout layers to prevent overfitting and ensure high validation accuracy.
* **Real-Time Inference:** Fast prediction response times (<100ms) suitable for real-time applications.
* **Robust Image Processing:** Automated resizing and normalization of input images using `PIL` and `NumPy`.
* **Scalable Architecture:** Packaged with Docker for easy deployment to AWS ECS, Azure, or Render.

## 🛠️ Tech Stack
* **Language:** Python 3.9
* **Deep Learning:** TensorFlow (Keras)
* **API Framework:** FastAPI, Uvicorn
* **Image Processing:** Pillow (PIL), NumPy
* **DevOps:** Docker

## 📂 Project Structure
```bash
Rock_Paper_Scissor-Classifier_CNN/
├── app.py                  # Main FastAPI application
├── Dockerfile              # Docker configuration for cloud deployment
├── requirements.txt        # Project dependencies
├── rps_cnn_model_V_new.keras  # Trained CNN Model Artifact
└── README.md               # Documentation
