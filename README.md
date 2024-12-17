# Real-time-Emotion-Detection-AR-App

## Project Overview
This project is an Augmented Reality (AR) application that labels emotions above people's heads in a live camera view. The application combines Computer Vision (CV) and AR technologies to perform real-time facial emotion recognition and overlay the detected emotions in an interactive AR interface.
Computer Vision Model: A pre-trained ONNX model for facial emotion recognition sourced from [ONNX.js Demo]([url](https://microsoft.github.io/onnxjs-demo/#/ ).
Face Tracking: Google's ARCore is leveraged to track faces and position AR labels dynamically.


## Features
Real-Time Emotion Detection: The application detects emotions such as happiness, sadness, anger, surprise, and more, based on facial expressions.
Live AR Labeling: Recognized emotions are displayed as dynamic labels above detected faces in the live camera view.
Efficient Model Integration: The emotion detection model is optimized using the ONNX format, ensuring lightweight and fast inference on edge devices.

Here is the low fidelity prototype of the project
![image](https://github.com/user-attachments/assets/fa2c85c4-7fca-4db0-b148-560b035a1436)


## Tech Stack
Computer Vision:
Model: Trained on FER+ Dataset (Facial Emotion Recognition Dataset).
Format: ONNX model for efficient inference.
Augmented Reality:
ARRCore SDK (for face tracking and positioning AR objects)
Frameworks and Tools:
Unity Editor and Visual Studio

## Set Up

1. Prerequisites
Ensure you have the following tools installed:

Unity Hub and Unity Editor (recommended version: 2021.3 LTS or later)
ARCore SDK for Unity (Google ARCore package)
Visual Studio (for scripting and Unity integration)
ONNX Runtime (Unity compatible version)
Barracuda for integrating ML models in Unity 

2. Integration Steps
   
Import the ONNX model into your AR project.
Use ARCore to detect and track faces in the camera feed.
Preprocess the detected faces (e.g., resizing, normalization) and pass them to the model for emotion classification.
Overlay AR labels based on the classification results above the corresponding faces in the live view.


4. Run the Application
   
Connect a compatible Android device.
Build and deploy the project using Unity.
Open the app and allow camera access to detect emotions in real time.


## Demo


