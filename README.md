# 🧔‍♂️ Face Detection with OpenCV

## 🔍 Overview

I was unable to hear my doorbell in my room and used to get a lot of scoldings for it lol. 
So i came up with a solution:
The plan is to run this locally on a old unusable smartphone as a door cam to play a bell sound on a remote speaker whenever the camera detects an human. 


This Python application utilizes OpenCV's pre-trained Haar Cascade Classifier to perform real-time face detection. It captures video from your webcam, detects faces, and highlights them with bounding boxes and play a bell sound. The script was ran locally on termux on an android phone.


## ⚙️ How It Works

The script uses OpenCV's `CascadeClassifier` with the `haarcascade_frontalface_default.xml` model to identify faces in each frame of the webcam feed. Detected faces are outlined with rectangles, and the application continues to run until manually closed.

It is ran on a old redmi mobile locally using to termux and used as a doorcam.

## 📦 Requirements

- `opencv-python` – for computer vision tasks
- `opencv-python-headless` – for headless environments (optional)

## 🔮 Future Additions:

- Adding feature `leave a message`

## 🛠️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/ahhyoushh/opencv-facedetection-python.git
   cd opencv-facedetection-python
