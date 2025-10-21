# 🧔‍♂️ Face Detection with OpenCV

## 🔍 Overview

This Python application utilizes OpenCV's pre-trained Haar Cascade Classifier to perform real-time face detection. It captures video from your webcam, detects faces, and highlights them with bounding boxes.

## ⚙️ How It Works

The script uses OpenCV's `CascadeClassifier` with the `haarcascade_frontalface_default.xml` model to identify faces in each frame of the webcam feed. Detected faces are outlined with rectangles, and the application continues to run until manually closed.

## 📦 Requirements

- `opencv-python` – for computer vision tasks
- `opencv-python-headless` – for headless environments (optional)

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ahhyoushh/opencv-facedetection-python.git
   cd opencv-facedetection-python
